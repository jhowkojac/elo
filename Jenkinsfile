pipeline {
    agente {
        docker {
            imagem " rubi "
        }
    }
    estágios {
        stage ( " Build " ) {
            passos {
                sh " bundle install "
            }
        }
    }
}