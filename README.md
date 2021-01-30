<h1>Api rest</h1>

api rest developed during the next level week 2

<p>
   To start the api use the command:  <b>yarn start</b> | <b>npm start</b>
  
   <b>guide on how to use the api:</b> 
  
   list classes: http://localhost:sua_porta/classes?week_day=DiaDaSemana&subject=Materia&time=Hora
   
   week_day- day of the week - starting at 0, which represents Sunday and so on
   subject - subject name
   time - class time
   
   list connections: http://localhost:sua_porta/classes?week_day=DiaDaSemana&subject=Materia&time=Hora
   
   week_day- day of the week - starting at 0, which represents Sunday and so on
   subject - subject name
   time - class time
   
   create classes: http://localhost:sua_porta/classes
   
   example json:
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
   
   create connections: http://localhost:3333/connections
   
   example json:
   
   {
   	"user_id":1
   }
    
   I advise you to use the Insomnia program to test the api
   
</p>

## Built With

<p align="left">
    <ul>
        <li><a href="https://nodejs.org/en/">NodeJs</a></li>
        <li><a href="https://www.sqlite.org/index.html">Sqlite</a></li>
        <li><a href="https://www.typescriptlang.org/">TypeScript</a></li>
    </ul>
</p>

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
