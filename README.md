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


/**
 * This script sets up an incoming payment on a receiving wallet address,
 * and a quote on the sending wallet address (after getting grants for both of the resources).
 *
 * The final step is asking for an outgoing payment grant for the sending wallet address.
 * Since this needs user interaction, you will need to navigate to the URL, and accept the interactive grant.
 *
 * To start, please add the variables for configuring the client & the wallet addresses for the payment.
 */

import {
  createAuthenticatedClient,
  OpenPaymentsClientError,
  isFinalizedGrant,
} from "@interledger/open-payments";
import readline from "readline/promises";

(async () => {
  const client = await createAuthenticatedClient({
    walletAddressUrl: "", // Make sure the wallet address starts with https:// (not $), and has no trailing slashes
    privateKey: "private.key",
    keyId: "",
  });

  const sendingWalletAddress = await client.walletAddress.get({
    url: "", // Make sure the wallet address starts with https:// (not $)
  });
  const receivingWalletAddress = await client.walletAddress.get({
    url: "", // Make sure the wallet address starts with https:// (not $)
  });

  console.log(
    "Got wallet addresses. We will set up a payment between the sending and the receiving wallet address",
    { receivingWalletAddress, sendingWalletAddress }
  );

  // Step 1: Get a grant for the incoming payment, so we can create the incoming payment on the receiving wallet address
  const incomingPaymentGrant = await client.grant.request(
    {
      url: receivingWalletAddress.authServer,
    },
    {
      access_token: {
        access: [
          {
            type: "incoming-payment",
            actions: ["read", "complete", "create"],
          },
        ],
      },
    }
  );

  console.log(
    "\nStep 1: got incoming payment grant for receiving wallet address",
    incomingPaymentGrant
  );

  // Step 2: Create the incoming payment. This will be where funds will be received.
  const incomingPayment = await client.incomingPayment.create(
    {
      url: receivingWalletAddress.resourceServer,
      accessToken: incomingPaymentGrant.access_token.value,
    },
    {
      walletAddress: receivingWalletAddress.id,
      incomingAmount: {
        assetCode: receivingWalletAddress.assetCode,
        assetScale: receivingWalletAddress.assetScale,
        value: "1000",
      },
    }
  );

  console.log(
    "\nStep 2: created incoming payment on receiving wallet address",
    incomingPayment
  );

  // Step 3: Get a quote grant, so we can create a quote on the sending wallet address
  const quoteGrant = await client.grant.request(
    {
      url: sendingWalletAddress.authServer,
    },
    {
      access_token: {
        access: [
          {
            type: "quote",
            actions: ["create", "read"],
          },
        ],
      },
    }
  );

  console.log(
    "\nStep 3: got quote grant on sending wallet address",
    quoteGrant
  );

  // Step 4: Create a quote, this gives an indication of how much it will cost to pay into the incoming payment
  const quote = await client.quote.create(
    {
      url: sendingWalletAddress.resourceServer,
      accessToken: quoteGrant.access_token.value,
    },
    {
      walletAddress: sendingWalletAddress.id,
      receiver: incomingPayment.id,
      method: "ilp",
    }
  );

  console.log("\nStep 4: got quote on sending wallet address", quote);

  // Step 5: Start the grant process for the outgoing payments.
  // This is an interactive grant: the user (in this case, you) will need to accept the grant by navigating to the outputted link.
  const outgoingPaymentGrant = await client.grant.request(
    {
      url: sendingWalletAddress.authServer,
    },
    {
      access_token: {
        access: [
          {
            type: "outgoing-payment",
            actions: ["read", "create"],
            limits: {
              debitAmount: {
                assetCode: quote.debitAmount.assetCode,
                assetScale: quote.debitAmount.assetScale,
                value: quote.debitAmount.value,
              },
            },
            identifier: sendingWalletAddress.id,
          },
        ],
      },
      interact: {
        start: ["redirect"],
        // finish: {
        //   method: "redirect",
        //   // This is where you can (optionally) redirect a user to after going through interaction.
        //   // Keep in mind, you will need to parse the interact_ref in the resulting interaction URL,
        //   // and pass it into the grant continuation request.
        //   uri: "https://example.com",
        //   nonce: crypto.randomUUID(),
        // },
      },
    }
  );

  console.log(
    "\nStep 5: got pending outgoing payment grant",
    outgoingPaymentGrant
  );
  console.log(
    "Please navigate to the following URL, to accept the interaction from the sending wallet:"
  );
  console.log(outgoingPaymentGrant.interact.redirect);

  await readline
    .createInterface({ input: process.stdin, output: process.stdout })
    .question("\nPlease accept grant and press enter...");

  let finalizedOutgoingPaymentGrant;

  const grantContinuationErrorMessage =
    "\nThere was an error continuing the grant. You probably have not accepted the grant at the url (or it has already been used up, in which case, rerun the script).";

  try {
    finalizedOutgoingPaymentGrant = await client.grant.continue({
      url: outgoingPaymentGrant.continue.uri,
      accessToken: outgoingPaymentGrant.continue.access_token.value,
    });
  } catch (err) {
    if (err instanceof OpenPaymentsClientError) {
      console.log(grantContinuationErrorMessage);
      process.exit();
    }

    throw err;
  }

  if (!isFinalizedGrant(finalizedOutgoingPaymentGrant)) {
    console.log(
      "There was an error continuing the grant. You probably have not accepted the grant at the url."
    );
    process.exit();
  }

  console.log(
    "\nStep 6: got finalized outgoing payment grant",
    finalizedOutgoingPaymentGrant
  );

  // Step 7: Finally, create the outgoing payment on the sending wallet address.
  // This will make a payment from the outgoing payment to the incoming one (over ILP)
  const outgoingPayment = await client.outgoingPayment.create(
    {
      url: sendingWalletAddress.resourceServer,
      accessToken: finalizedOutgoingPaymentGrant.access_token.value,
    },
    {
      walletAddress: sendingWalletAddress.id,
      quoteId: quote.id,
    }
  );

  console.log(
    "\nStep 7: Created outgoing payment. Funds will now move from the outgoing payment to the incoming payment.",
    outgoingPayment
  );

  process.exit();
})();
