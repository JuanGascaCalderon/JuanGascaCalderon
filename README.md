<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000000;
            margin: 0;
            padding: 0;
            color: #ffffff; /* Cambiamos el color del texto a blanco para mejor contraste */
        }
        .container {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            padding: 20px;
            background-color: #999999; /* Cambiar el color de fondo a un gris más suave */
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px; /* Agregamos un margen inferior para separar los contenedores */
        }
        .container h1 {
            margin: 10px 0;
            text-align: center;
            color: #000000; /* Mantener el color del texto negro para el contraste */
        }
        .container p {
            text-align: center;
            font-size: 14px;
            line-height: 1.6;
            color: #000000; /* Mantener el color del texto negro para el contraste */
            font-weight: bold; /* Hacer el texto en negrita */
            position: relative; /* Establecer la posición relativa */
            display: inline-block; /* Hacer que el elemento sea un bloque en línea */
        }
    .container p::after {
        content: "";
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: linear-gradient(to bottom right, transparent 50%, #CCCCCC 50%);
        z-index: -1;
        transform: skew(-15deg);
    }
    .code-container {
        background-color: #999999; /* Cambiamos el color de fondo del nuevo contenedor */
        padding: 0px;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        display: flex;
        flex-wrap: wrap; /* Permitimos que los elementos se envuelvan a la siguiente línea */
        align-items: center;
        justify-content: center; /* Alinear los elementos al centro horizontalmente */
        margin-top: 10px; /* Agregamos un margen superior para separar del contenido anterior */
        overflow: auto; /* Añadimos un desplazamiento si el contenido supera el tamaño del contenedor */
    }
    .code-container h2 {
        width: 90%; /* Asegurarse de que el título ocupe todo el ancho del contenedor */
        color: #000000; /* Mantener el color del texto negro para el contraste */
        font-family: Arial, sans-serif; /* Usar la misma fuente que el contenedor anterior */  
        font-weight: bold; /* Hacer el texto en negrita */
        margin-bottom: 5px; /* Agregamos margen inferior al título para separarlo de los distintivos */     
    }
    .badge {
        margin: 5px; /* Agregamos un pequeño margen alrededor de los distintivos */
        height: auto; /* Permitir que la altura se ajuste automáticamente para mantener la proporción */
    }
    </style>
</head>
<body>
    <div class="container">
        <img src="https://media.giphy.com/media/zhYSVCirREeIZtONCI/giphy.gif?cid=790b7611eepvlhdurz855phgnw0u0it1yi1hw1rsj26jp868&ep=v1_stickers_search&rid=giphy.gif&ct=s" width="120" alt="GIF Image"/> 
        <h1>Hey!👋 Nice to meet you 💻</h1> 
        <p>I'm Juan Gasca, Mechatronics Engineer focus on Data Analyst 📊.</p>
    </div>
    <!-- Nuevo contenedor para "Things I code with" -->
     <div class="code-container">
        <h2>💻Tech Stack</h2>
        <!-- Badges de tecnologías -->
        <img class="badge" src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python Badge">
        <img class="badge" src="https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI Badge">
        <img class="badge" src="https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure Badge">
        <img class="badge" src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git Badge">
        <img class="badge" src="https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white" alt="Keras Badge">
        <img class="badge" src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black" alt="Matplotlib Badge">
        <img class="badge" src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy Badge">
        <img class="badge" src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas Badge">
        <img class="badge" src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn Badge">
        <img class="badge" src="https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white" alt="SciPy Badge">
        <img class="badge" src="https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white" alt="TensorFlow Badge">
        <img class="badge" src="https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white" alt="Plotly Badge">
        <img class="badge" src="https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL Badge">
    </div>
</body>
</html>
