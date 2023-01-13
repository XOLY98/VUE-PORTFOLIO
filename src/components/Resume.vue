<template>
  <h1>RESUME</h1>

 
          
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


</style>