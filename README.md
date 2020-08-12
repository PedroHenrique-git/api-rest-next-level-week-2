<h1 align="center">Api rest desenvolvida durante a next level week 2</h1>

<p align="left">
  Para iniciar a api use o comando: yarn start | npm start
  
   guia de como usar a api 
  
   listar classes: http://localhost:sua_porta/classes?week_day=DiaDaSemana&subject=Materia&time=Hora
   
   week_day- dia da semana - começando em 0, que representa domingo e assim por diante
   subject - nome da materia
   time - hora da aula
   
   listar connections: http://localhost:sua_porta/classes?week_day=DiaDaSemana&subject=Materia&time=Hora
   
   week_day- dia da semana - começando em 0, que representa domingo e assim por diante
   subject - nome da materia
   time - hora da aula
   
   criar classes: http://localhost:sua_porta/classes
   
   json de exemplo:
   {
      "name":"Daniel",
      "avatar":"exemplo.png",
      "whatsapp": "23123123123",
      "bio":"asdasdadasdasdasdasd",
      "subject": "matemática",
      "cost": 80,
      "schedule":[
        {"week_day": 1, "from":"8:00", "to": "12:00"},
        {"week_day": 3, "from":"10:00", "to": "18:00"}, 
        {"week_day": 4, "from":"8:00", "to": "12:00"} 
      ]
   }
   
   criar connections: http://localhost:3333/connections
   
   json de exemplo:
   
   {
   	"user_id":1
   }
    
   aconselho que use o programa Insomnia para testar a api
   
</p>

<p align="left">
    <ul>
        <li><a href="https://nodejs.org/en/">🔗 NodeJs</a></li>
        <li><a href="https://www.sqlite.org/index.html">🔗 Sqlite</a></li>
        <li><a href="https://www.typescriptlang.org/">🔗 TypeScript</a></li>
    </ul>
</p>

<p align="left">
    Clonar projeto: git clone https://github.com/PedroHenrique-git/crud-php.git
</p>
