def target_node='SlaveNode'
pipeline { 
    #agent {label "${target_node}"}
     agent {label "${target_node}"}
        stages {
            stage('Build Stage') {		
                steps {               
                    echo "from Build Stage:" 
			sh "printenv"
					}
            }		
    
            stage('Deploy Stage') {
                steps {
                    echo "From Deploy Stage "
                                    
                    }                              
                }
    }
}
