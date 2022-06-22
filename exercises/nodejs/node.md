<details>
    <summary>What is Node.js</summary><br>
    <b>
        Node.js is Server-side scripting which is used to build scalable programs. It is a web application framework built on Google Chrome's JavaScript Engine. This runtime facilitates you to execute a JavaScript code on any machine outside a browser.4
    </b>
</details>

<details>
    <summary>Why we use node js</summary><br>
    <b>
        1. It is easy to learn Node.js.<br>
        2. The scalability offered.<br>
        3. The Mobile-friendly, Cross-platform, and Dev-Friendly nature of Node.js.<br>
        4. Node.js is light and fast.<br>
        5. The many hosting providers available.<br>
        6. Highly extensible<br>
        7. Its caching ability
    </b>
</details>

<details>
    <summary>NodeJS 5 Packages</summary><br>
    <b>
        1. Express.<br>
        2. Lodash.<br>
        3. Moment.js.<br>
        4. Axios.<br>
        5. Morgan.<br>
        6. MySQL.<br>
        7. Nodemon.<br>
        7. Nodemailer.<br>
        7. Molecular.<br>
        7. Agenda.
    </b>
</details>

<details>
    <summary>What is REPL</summary><br>
    <b>
        Node. js Read-Eval-Print-Loop (REPL) is an easy-to-use command-line tool, used for processing Node. js expressions. It captures the user's JavaScript code inputs, interprets, and evaluates the result of this code.
    </b>
</details>

<details>
    <summary>What is NPM</summary><br>
    <b>
        NPM stands for Node Package Manager. npm is the package manager for the Node JavaScript platform.
    </b>
</details>

<details>
    <summary>What is NPM</summary><br>
    <b>
        NPM stands for Node Package Manager. npm is the package manager for the Node JavaScript platform.
    </b>
</details>

<details>
    <summary>Node js is Single Thereaded or Multi Thereaded</summary><br>
    <b>
        Yes Node is a single threaded application with event looping.
    </b>
</details>

<details>
    <summary>First-Class Function</summary><br>
    <b>
        When functions in that language are treated like any other variable. 
        For example, in such a language, a function can be assigned as a value to a variable, can be passed as an argument to other functions and can be returned by another function.
    </b>
</details>

<details>
    <summary>What is promisses</summary></br>
    <b>
        A promise is an object which represents the result of an asynchronous operation which is either resolved or rejected (with a reason).
        const callMe=new Promise((resolve,reject)=>{
        if(true){
        resolve("Resolve");
        }else{
        reject("False");
        }
        })
        callMe
        .then(result=>{
        console.log(result);
        })
        .catch(err=>{
        console.log(err)
        })
    </b>
</details>

<details>
    <summary>Shallow Copy</summary></br>
    <b>
        A shallow copy means that certain (sub-)values are still connected to the original variable. 
    </b>
</details>

<details>
    <summary>Deep Copy</summary></br>
    <b>
        A deep copy means that all of the values of the new variable are copied and disconnected from the original variable.
    </b>
</details>

<details>
    <summary>Deep Copy</summary></br>
    <b>
        “Self-Invoking” function is a type of function that is invoked or called automatically after its definition.
        (function (parameters) {
            //body of the function
        })(arguments);
    </b>
</details>

<details>
    <summary>what is this keyword</summary></br>
    <b>
        “This” keyword refers to an object that is executing the current piece of code. It references the object that is executing the current function. If the function being referenced is a regular function, “this” references the global object.
    </b>
</details>

<details>
    <summary>What is function constructor</summary></br>
    <b>
        A constructor is a special function that creates and initializes an object instance of a class.
    </b>
</details>

<details>
    <summary>What is Closure</summary></br>
    <b>
        A closure gives you access to an outer function's scope from an inner function.
        <br/>
        function makeFunc() {
            var name = 'Mozilla';
            function displayName() {
                alert(name);
            }
            return displayName;
        }
        var myFunc = makeFunc();
        myFunc();
    </b>
</details>