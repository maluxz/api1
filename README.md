# CryptoContentStore (English)
- API using the Express.js Framework and connecting to a MySQL and/or MSSQL Server database (No ORM usage such as Sequelize 😞).

## Description
- CryptoContentStore is a content store project that allows users to make purchases of digital products using cryptocurrencies. This project was initiated as part of the Full Stack Web Development course at the Technological Institute of Delicias (TecNM).

## Main Features

- **Users and Authentication:**
  - The user has a username, a password encrypted with bcrypt, an optional email, and the amount of tokens available for purchases.
  - Login is managed using JWT (JSON Web Tokens) for secure authentication.

- **Address Management:**
  - Each user can generate new deposit addresses that are associated with their user ID upon creation.

- **Transactions and Cryptocurrencies:**
  - Once the user has generated a deposit address and made a deposit, the database records and processes the transaction, adding the corresponding amount of tokens to the amount of cryptocurrency deposited in the address. Additionally, this transaction can be verified from any public network block explorer.
 
- **Digital Products:**
  - The store plans to offer digital products for purchase from anywhere in the world without the need for centralized intermediaries thanks to the crypto's network (BTC Testnet).

## Project Structure

The project has been carefully organized to improve code clarity and maintainability. The structure includes:

- **Folders:**
  - Folders are logically distributed to house specific components of the project (e.g., authentication, transactions, products, etc.).

- **Routes and Endpoints:**
  - Routes and endpoints have been clearly defined to facilitate navigation and understanding of the application flow.

## Author
- [Mario Lujan](https://github.com/maluxz)

---

# CryptoContentStore (Español)
- API utilizando el Framework Express.js y que conecta a una base de datos MySQL y/o MSSQL Server (No se cuenta con uso de ORM como Sequelize 😞).

## Descripción
- CryptoContentStore es un proyecto de tienda de contenido que permite a los usuarios realizar compras de productos digitales utilizando criptomonedas. Este proyecto fue iniciado como parte de la materia de Desarrollo Web Full Stack del Instituto Tecnológico de Delicias (TecNM).

## Características Principales

- **Usuarios y Autenticación:**
  - El usuario cuenta con un nombre de usuario, una contraseña cifrada con bcrypt, un email opcional y la cantidad de fichas disponibles para hacer compras.
  - El inicio de sesión se gestiona mediante tokens JWT (JSON Web Tokens) para una autenticación segura.

- **Gestión de Direcciones:**
  - Cada usuario puede generar nuevas direcciónes de deposito que al crearse se asocian a su ID de usuario.

- **Transacciones y Criptomonedas:**
  - Una vez que el usuario haya generado alguna dirección de deposito y haga un deposito la base de datos registra y procesa la transacción agregando la cantidad de fichas correspondiente a la cantidad de criptomoneda depositada en la dirección, además esta transacción se puede verificar desde cualquier explorador de bloques de la red pública.
 
- **Productos Digitales:**
  - La tienda planea ofrecer productos digitales para compra desde cualquier parte del mundo sin necesidad de intermediarios gracias a la red.

## Estructura del Proyecto

El proyecto ha sido organizado cuidadosamente para mejorar la claridad y mantenibilidad del código. La estructura incluye:

- **Carpetas:**
  - Las carpetas están distribuidas de manera lógica para albergar componentes específicos del proyecto (por ejemplo, autenticación, transacciones, productos, etc.).

- **Rutas y Endpoints:**
  - Las rutas y endpoints han sido definidos de manera clara para facilitar la navegación y comprensión del flujo de la aplicación.

## Autor
- [Mario Lujan](https://github.com/maluxz)
