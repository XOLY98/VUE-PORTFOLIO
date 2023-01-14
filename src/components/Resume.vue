<template>
  <h1>RESUME</h1>
<section style="background-color: #F0F2F5;">
  <div class="container py-5">
    <div class="main-timeline">
      <div class="timeline left">
        <div class="card">
          <div class="card-body p-4">
            <h3>2017</h3>
            <p class="mb-0">Lorem ipsum dolor sit amet, quo ei simul congue exerci, ad nec admodum perfecto
              mnesarchum, vim ea mazim fierent detracto. Ea quis iuvaret expetendis his, te elit voluptua
              dignissim per, habeo iusto primis ea eam.</p>
          </div>
        </div>
      </div>
      <div class="timeline right">
        <div class="card">
          <div class="card-body p-4">
            <h3>2016</h3>
            <p class="mb-0">Lorem ipsum dolor sit amet, quo ei simul congue exerci, ad nec admodum perfecto
              mnesarchum, vim ea mazim fierent detracto. Ea quis iuvaret expetendis his, te elit voluptua
              dignissim per, habeo iusto primis ea eam.</p>
          </div>
        </div>
      </div>
      <div class="timeline left">
        <div class="card">
          <div class="card-body p-4">
            <h3>2015</h3>
            <p class="mb-0">Lorem ipsum dolor sit amet, quo ei simul congue exerci, ad nec admodum perfecto
              mnesarchum, vim ea mazim fierent detracto. Ea quis iuvaret expetendis his, te elit voluptua
              dignissim per, habeo iusto primis ea eam.</p>
          </div>
        </div>
      </div>
      <div class="timeline right">
        <div class="card">
          <div class="card-body p-4">
            <h3>2012</h3>
            <p class="mb-0">Lorem ipsum dolor sit amet, quo ei simul congue exerci, ad nec admodum perfecto
              mnesarchum, vim ea mazim fierent detracto. Ea quis iuvaret expetendis his, te elit voluptua
              dignissim per, habeo iusto primis ea eam.</p>
          </div>
        </div>
      </div>
      <div class="timeline left">
        <div class="card">
          <div class="card-body p-4">
            <h3>2011</h3>
            <p class="mb-0">Lorem ipsum dolor sit amet, quo ei simul congue exerci, ad nec admodum perfecto
              mnesarchum, vim ea mazim fierent detracto. Ea quis iuvaret expetendis his, te elit voluptua
              dignissim per, habeo iusto primis ea eam.</p>
          </div>
        </div>
      </div>
      <div class="timeline right">
        <div class="card">
          <div class="card-body p-4">
            <h3>2007</h3>
            <p class="mb-0">Lorem ipsum dolor sit amet, quo ei simul congue exerci, ad nec admodum perfecto
              mnesarchum, vim ea mazim fierent detracto. Ea quis iuvaret expetendis his, te elit voluptua
              dignissim per, habeo iusto primis ea eam.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
 
          
</template>
<script>
export default {
    data() {
        return {
            skills:[{
         name:"HTML",
         percentage:"85%"
            },
            {
                name:"CSS",
                percentage:"70%"
            },
            {
                name:"JAVASCRIPT",
                percentage:"50%"
            },
            {
                name:"SQL/DATABASE",
                percentage:"50%"
            }
            ],
            education:[
                {
                    name:"MZOMHLE HIGH SCHOOL",
                    year:"2015",
                    position:"Matriculant",
                },
                {
                    name:"LIFE CHOICES CODING ACADEMY",
                    year:"Sept 2022-March 2023",
                    position:"Student",
                },
            ],
            experience:[{
                companyName:"Mbatha Mlambo(Avis car-rental)",
                position:"General-worker",
                period:"Oct 2017-March 2020",
                refrence:"Mr.N.Dube(073 566 3333)"
            },
            {
                companyName:"NOMLINGANISELO PRIMARY SCHOOL",
                position:"Teacher Assistant",
                period:"Dec 2020-April 2021",
                refrence:"Mr.M.Mzinda(021 374 6638)"
            },
            {
                companyName:"KHUSELA CEP",
                position:"Call centre Specialist& Direct Marketing",
                period:"March 2020-Sep 2020",
                refrence:"Mr.G.Almazein(021 706 0039)"
            }
            ],
        }
    },
}
</script>
<style scoped>
h1{
    font-style:bold;
    color:#A865C9;
    text-decoration: underline double #A865C9;
    text-underline-position: under;
    text-align:center;
}
/* The actual timeline (the vertical ruler) */
.main-timeline {
  position: relative;
}

/* The actual timeline (the vertical ruler) */
.main-timeline::after {
  content: "";
  position: absolute;
  width: 6px;
  background-color: #939597;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -3px;
}

/* Container around content */
.timeline {
  position: relative;
  background-color: inherit;
  width: 50%;
}

/* The circles on the timeline */
.timeline::after {
  content: "";
  position: absolute;
  width: 25px;
  height: 25px;
  right: -13px;
  background-color: #939597;
  border: 5px solid #f5df4d;
  top: 15px;
  border-radius: 50%;
  z-index: 1;
}

/* Place the container to the left */
.left {
  padding: 0px 40px 20px 0px;
  left: 0;
}

/* Place the container to the right */
.right {
  padding: 0px 0px 20px 40px;
  left: 50%;
}

/* Add arrows to the left container (pointing right) */
.left::before {
  content: " ";
  position: absolute;
  top: 18px;
  z-index: 1;
  right: 30px;
  border: medium solid white;
  border-width: 10px 0 10px 10px;
  border-color: transparent transparent transparent white;
}

/* Add arrows to the right container (pointing left) */
.right::before {
  content: " ";
  position: absolute;
  top: 18px;
  z-index: 1;
  left: 30px;
  border: medium solid white;
  border-width: 10px 10px 10px 0;
  border-color: transparent white transparent transparent;
}

/* Fix the circle for containers on the right side */
.right::after {
  left: -12px;
}

/* Media queries - Responsive timeline on screens less than 600px wide */
@media screen and (max-width: 600px) {
  /* Place the timelime to the left */
  .main-timeline::after {
    left: 31px;
  }

  /* Full-width containers */
  .timeline {
    width: 100%;
    padding-left: 70px;
    padding-right: 25px;
  }

  /* Make sure that all arrows are pointing leftwards */
  .timeline::before {
    left: 60px;
    border: medium solid white;
    border-width: 10px 10px 10px 0;
    border-color: transparent white transparent transparent;
  }

  /* Make sure all circles are at the same spot */
  .left::after,
  .right::after {
    left: 18px;
  }

  .left::before {
    right: auto;
  }

  /* Make all right containers behave like the left ones */
  .right {
    left: 0%;
  }
}

</style>