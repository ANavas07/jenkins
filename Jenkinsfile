pipeline{
    agent any
    environment {
        CONTENEDOR = 'mi-contenedor-practica'
        IMAGEN = 'mi-imagen-practica'
    }
    stages{
        stage('Preparar Entorno Docker '){
            sh "docker stop ${env.CONTENEDOR} || true"
            sh "docker rm ${env.CONTENEDOR} || true"
        }
        stage('Clonar repositorio'){

        }
        stage('Construir imagen Docker'){

        }
        stage('Desplegar en docker'){

        }
    }
}