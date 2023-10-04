**Título: Fundamentos de la Programación con JavaScript**

**Introducción (5 minutos)**

- Explica brevemente qué es JavaScript: un lenguaje de programación ampliamente utilizado en el desarrollo web para crear interactividad en las páginas web.

**0.1 Qué es JavaScript**

- Presenta JavaScript como un lenguaje de programación que se utiliza para crear interactividad en las páginas web.
- Explica que JavaScript se ejecuta en el navegador del usuario y que no es lo mismo que Java.
- Menciona que JavaScript se utiliza para crear aplicaciones web, aplicaciones móviles, servidores, robots, etc.

**0.2 Herramientas de Desarrollo Web**

- Explica que para crear aplicaciones web, necesitamos tres herramientas básicas: HTML, CSS y JavaScript.
- HTML: Define la estructura y el contenido de una página web.
- CSS: Define el estilo y la apariencia de una página web.
- JavaScript: Define la interactividad de una página web.

**0.3 Modern frameworks**
Modern web development often involves using a combination of frameworks, libraries, and technology stacks to create efficient and scalable web applications. Here's an overview of some popular modern frameworks and technology stacks:

**0.3.1. Front-End Frameworks:**

   a. **React:** Developed by Facebook, React is a popular JavaScript library for building user interfaces. It follows a component-based architecture and is often used with tools like Redux for state management.

   b. **Angular:** Developed by Google, Angular is a full-fledged front-end framework that provides a comprehensive solution for building web applications. It includes features like two-way data binding, dependency injection, and routing.

   c. **Vue.js:** Vue is another JavaScript framework for building user interfaces. It's known for its simplicity and ease of integration into existing projects.

**0.3.2. Back-End Frameworks:**

   a. **Node.js:** While not a traditional framework, Node.js is a runtime environment that allows you to run JavaScript on the server-side. It's commonly used with Express.js, a minimalist web application framework for building APIs and web applications.

   b. **Ruby on Rails:** Ruby on Rails is a popular framework for building web applications quickly. It follows the Model-View-Controller (MVC) pattern and emphasizes convention over configuration.

   c. **Django:** Django is a Python web framework known for its robustness and scalability. It follows the MVC pattern and includes built-in features for authentication, database modeling, and more.

**0.3.3. Full-Stack Frameworks:**

   a. **MEAN Stack:** MEAN stands for MongoDB, Express.js, Angular, and Node.js. It's a full-stack JavaScript framework for building web applications, with MongoDB as the database.

   b. **MERN Stack:** MERN stands for MongoDB, Express.js, React, and Node.js. Like MEAN, it's a full-stack JavaScript framework, but it uses React for the front end.

**0.3.4. Mobile App Development:**

   a. **React Native:** This framework allows you to build mobile applications for iOS and Android using React and JavaScript. It enables code reuse between web and mobile apps.

   b. **Flutter:** Developed by Google, Flutter is a UI toolkit for building natively compiled applications for mobile, web, and desktop from a single codebase.

   c. **Ionic:** Ionic is an open-source UI toolkit for building high-quality mobile and desktop apps using web technologies like HTML, CSS, and JavaScript.


**0.3.5. DevOps and Deployment:**

   a. **Docker:** Docker is a platform for containerizing applications, making it easier to package and deploy them consistently across different environments.

   b. **Kubernetes:** Kubernetes is an open-source container orchestration platform that automates the deployment, scaling, and management of containerized applications.

**0.3.6. Serverless Computing:**

   a. **AWS Lambda:** AWS Lambda is a serverless compute service that allows you to run code in response to events without managing servers. It's often used with other AWS services to create serverless applications.

   b. **Firebase:** Firebase is a mobile and web application development platform that provides a variety of tools and services to help you build apps quickly. It includes features like authentication, real-time database, hosting, and more.

   c. **Vercel:** Vercel is a cloud platform for static sites and serverless functions. It's often used for hosting Next.js applications.


**0.3.7. Database Systems:**

   a. **MySQL, PostgreSQL, MongoDB:** These are popular databases for storing and retrieving data in web applications. MySQL and PostgreSQL are relational databases, while MongoDB is a NoSQL database.

   b. **Back-End as a Service (BaaS):** BaaS platforms like Firebase and AWS Amplify provide managed services for common back-end tasks like authentication, database, storage, and more.


**0.3.8. Version Control and Collaboration:**

   a. **Git:** Git is a distributed version control system widely used for managing code repositories and collaborating with others.

   b. **GitHub, GitLab, Bitbucket:** These are platforms that provide hosting for Git repositories and offer additional collaboration and CI/CD (Continuous Integration/Continuous Deployment) features.

Modern web development often involves selecting the right combination of these technologies based on project requirements, scalability needs, and development team expertise. The choice of frameworks and stacks can greatly impact the efficiency and success of a web development project.


**1. Conceptos Básicos (10 minutos)**

- Variables: Son contenedores que almacenan datos. Puedes declarar variables con `var`, `let` o `const`.
- Tipos de datos: Los tipos de datos más comunes son números, cadenas de texto (strings) y booleanos.
- Operadores: Explica operadores aritméticos (+, -, *, /), operadores de comparación (==, ===, !=, !==), y operadores lógicos (&&, ||, !).
- Console.log: Explica cómo usar `console.log` para imprimir mensajes en la consola del navegador.

**1.1 Ejercicios con variables**

- Crea una variable para almacenar tu nombre.

```js
var myName = "John";
```

- Crea una variable para almacenar tu edad.

```js
var myAge = 30;
```

- Crea una variable para almacenar tu país de origen.

```js
var myCountry = "USA";
```

- Crea una variable para almacenar si te gusta JavaScript o no (true o false).

```js
var likeJavaScript = true;
```

- Imprime en la consola el contenido de cada variable.

```js
console.log(myName);
console.log(myAge);
console.log(myCountry);
console.log(likeJavaScript);
```

**1.2 Ejercicios con operadores**

- Crea una variable para almacenar el número de horas que duermes cada noche.
  - Solución:

```js
var hoursOfSleep = 8;
```
- Crea una variable para almacenar el número de horas que trabajas cada día.

```js
var hoursOfWork = 8;
```

- Crea una variable para almacenar el número de horas que pasas en la escuela cada día.

```js
var hoursOfSchool = 6;
```

- Crea una variable para almacenar el número total de horas que pasas despierto cada día.

```js
var hoursAwake = hoursOfSleep + hoursOfWork + hoursOfSchool;
```

- Imprime en la consola el número total de horas que pasas despierto cada día.

```js
console.log(hoursAwake);
```

**1.3 Ejercicios con tipos de datos**

- Crea una variable para almacenar el número de horas que duermes cada noche.
- Crea una variable para almacenar el número de horas que trabajas cada día.
- Crea una variable para almacenar el número de horas que pasas en la escuela cada día.
- Crea una variable para almacenar el número total de horas que pasas despierto cada día.
- Imprime en la consola el número total de horas que pasas despierto cada día.

**2. Estructuras de Control (15 minutos)**

- If-else: Cómo usar declaraciones condicionales para tomar decisiones en tu código.
- Bucles: Introduce los bucles `for` y `while` para repetir tareas.
- Ejemplo: Crea un programa simple que determine si un número es par o impar usando un `if`.

**2.1 Ejercicios con if-else**

- Crea una variable para almacenar tu edad.

```js
var myAge = 30;
```

- Crea una declaración condicional que determine si eres mayor de edad o no.

```js
if (myAge >= 18) {
  console.log("Eres mayor de edad");
} else {
  console.log("Eres menor de edad");
}
```

- Crea una variable para almacenar tu país de origen.
  
```js
var myCountry = "USA";
```

- Crea una declaración condicional que determine si vives en Estados Unidos o no.

```js
if (myCountry === "USA") {
  console.log("Vives en Estados Unidos");
} else {
  console.log("No vives en Estados Unidos");
}
```

**3. Funciones (15 minutos)**

- Define qué son las funciones y cómo se pueden utilizar para organizar y reutilizar código.
- Parámetros y argumentos: Cómo pasar información a las funciones.
- Ejemplo: Crea una función que calcule el área de un rectángulo.

**4. Arrays (10 minutos)**

- Explica qué son los arreglos (arrays) y cómo se utilizan para almacenar conjuntos de datos.
- Métodos de arreglo: Algunos ejemplos básicos de métodos como `push`, `pop`, `shift`, y `unshift`.

**5. Objetos (10 minutos)**

- Presenta los objetos como estructuras de datos clave-valor.
- Cómo crear, acceder y modificar propiedades de objetos.

**6. Eventos y DOM (15 minutos)**

- Explica cómo JavaScript puede interactuar con el Document Object Model (DOM) para hacer que las páginas web sean interactivas.
- Introduce eventos y cómo usarlos para responder a acciones del usuario.

**Ejercicio Práctico (10 minutos)**

- Proporciona a los estudiantes un ejercicio práctico simple que involucre los conceptos aprendidos, como la manipulación del DOM para cambiar el contenido de una página web.

**Preguntas y Respuestas (5 minutos)**

- Responde a las preguntas de los estudiantes y refuerza los conceptos clave.

**Conclusion (5 minutos)**

- Resalta la importancia de los fundamentos de JavaScript en el desarrollo web y la programación en general.
- Anima a los estudiantes a practicar y seguir aprendiendo.

**Recursos adicionales (si hay tiempo):**

- Menciona recursos en línea donde los estudiantes pueden aprender más sobre JavaScript, como tutoriales, documentación oficial y comunidades en línea.

Este plan de una hora proporciona una introducción sólida a los fundamentos de la programación con JavaScript y permite tiempo para la práctica y preguntas. ¡Espero que sea útil para tu clase!