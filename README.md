 ¿Cuál es el problema? 
La administración colectiva del dinero entre grupos de confianza (como amigos, familias  y comunidades) suele hacerse de manera informal, lo que genera falta de control, poca transparencia y dificultades para cumplir metas comunes. Nuestra encuesta reveló que 8 de cada 10 personas están de acuerdo en la importancia del ahorro social, lo que confirma que existe interés real en soluciones colaborativas; sin embargo, actualmente no cuentan con una herramienta digital confiable, segura y sencilla que les permita organizar sus aportes, transparentar el uso de los recursos y fomentar hábitos de consumo responsable.
¿Que tecnologias usaran?
Las tecnologias que vamos a utilizar son las siguientes:
-Nodejs
-Html
-Estilos 
-Visual code 
-Las wallet de interledger Test Wallet
-Bloc de notas 
-Javascript 

¿Cual es la solucion?
Para responder a la necesidad detectada, se plantea el desarrollo de una aplicación web de monedero colaborativo social, diseñada para que un anfitrión pueda crear un espacio financiero privado al cual invite únicamente a las personas de su confianza. La plataforma permitirá organizar aportaciones, registrar movimientos de manera transparente y establecer metas comunes de ahorro o consumo responsable.De esta manera, la solución no solo resuelve el problema de informalidad y desorganización en el manejo del dinero colectivo, sino que también promueve la confianza entre los participantes, fomenta hábitos financieros responsables y abre la posibilidad de impulsar el desarrollo económico a través de un consumo planificado y colaborativo.

#resultados {
            margin-top: 2em;
            text-align: center;
            font-size: 1.2em;
        }
        #resultados h2 {
            color: #4CAF50;
        }
        .payment-button {
            background-color: #4CAF50;
            color: white;
            padding: 12px 24px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
            margin: 0.5em;
            transition: background-color 0.3s;
        }
        .payment-button:hover {
            background-color: #388e3c;
        }
        .wallet-input {
            margin-top: 1em;
            display: none;
        }
        .wallet-input input {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        .back-button {
            margin-top: 2em;
            padding: 12px 24px;
            background-color: #555;
            color: white;
            border-radius: 5px;
            text-decoration: none;
            display: inline-block;
            transition: background-color 0.3s;
        }
        .back-button:hover {
            background-color: #333;
        }
    </style>
</head>
<body>

#invitados-lista {
            margin-top: 2em;
            text-align: left;
        }
        #invitados-lista h2 {
            color: #4CAF50;
        }
        #invitados-lista .invitado-item {
            display: inline-block;
            margin: 0.5em;
        }
        .invitado-button {
            background-color: #008CBA;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            font-size: 1em;
            transition: background-color 0.3s, transform 0.3s;
        }
        .invitado-button:hover {
            background-color: #005f6b;
            transform: scale(1.05);
        }
        .contact-form {
            display: none;
            margin-top: 1em;
            padding: 1em;
            border: 1px solid #ccc;
            border-radius: 8px;
            background-color: #f9f9f9;
        }
        .contact-form .form-group {
            margin-bottom: 1em;
        }
        .contact-form button {
            background-color: #2196F3;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .back-button {
            margin-top: 2em;
            padding: 12px 24px;
            background-color: #555;
            color: white;
            border-radius: 5px;
            text-decoration: none;
            display: inline-block;
            transition: background-color 0.3s;
        }
        .back-button:hover {
            background-color: #333;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Invitar a tus amigos 🤝</h1>
        <p>Escribe el nombre del invitado y haz clic en "Agregar" para enviar una invitación.</p>

        <div class="form-group">
            <label for="nombreInvitado">Nombre del Invitado:</label>
            <input type="text" id="nombreInvitado" placeholder="Escribe el nombre aquí">
            <button class="add-button" onclick="agregarInvitado()">Agregar</button>
        </div>

        <div id="invitados-lista">
            <h2>Invitados</h2>
            <div id="listaBotonesInvitados"></div>
        </div>

        <div id="contactFormContainer" class="contact-form">
            <h2 id="contactFormTitle">Enviar invitación a: </h2>
            <div class="form-group">
                <label for="emailInput">Correo Electrónico:</label>
                <input type="email" id="emailInput" placeholder="correo@ejemplo.com">
                <button onclick="enviarInvitacion('email')">Enviar por Correo</button>
            </div>
            <div class="form-group">
                <label for="phoneInput">Número de Teléfono:</label>
                <input type="tel" id="phoneInput" placeholder="55-1234-5678">
                <button onclick="enviarInvitacion('sms')">Enviar por SMS</button>
            </div>
        </div>

        




 ¿Cuáles son los beneficios?
     Fomento de la disciplina y el habito de ahorro
     Acceso al crédito y el habito de ahorro
     Solidaridad y apoyo mutuo
     Rendimientos y beneficios adicionales
     Seguridad economica
     Beneficios Fiscales

¿Cual es su arquitectura/stick simple?
Usaremos visual studio y tambien las wallets de interledger para toder crear una conexion entre dos personas mediante los links, siendo nmás facil ahorrar mediante open payments.
}

¿Que funciones son indispensables? 
Que cada usuario tenga su billetera electronica en la wallet de interledger despues de eso cada quien tendra que tener su (Payment Pointers) al tenerlo tambien creamos la url para que se pueda completar la transaccion y se vea reflejada en nuestra caja de ahorros.


¿Quien sera responsable de construir que parte?
Adan estara encargado de realizar la pagina web con botones y estilos 
joseline y Farit estaran encargados de realizar las conexiones entre nodejs y visual code al igual que las conexiones entre visual code y las wallets 
alan estara encargado de realizar la pagina web junto con adan y encargado de buscar informacion y diseño**
