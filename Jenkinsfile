library identifier: 'shared_libs_tag_demo@v1.0',
    retriever: modernSCM([
      $class: 'GitSCMSource',
      // remote: 'https://github.com/suman2826/jenkins-shared-libs.git'
      remote: 'https://github.com/suman2826/shared_libs_tag_demo.git'
])
jenkinsForJava()

//   pipeline {
//     agent any
//        options {
//         disableConcurrentBuilds()
//               skipDefaultCheckout()
//     }
//        parameters {
//               choice (
//                      name: "deploymentTrack",
//                      choices: ['cr','ar1','ar2', 'pr'],
//                      description: "choose tracl"
//                      )
//        }
      
//        stages {
//            stage("Tools initialization") {
//                steps {
//                    echo "Started"
//                  echo "${env.BRANCH_NAME}"
//                   echo "${env.GIT_COMMIT}"
//                    echo "${env.GIT_PREVIOUS_COMMIT}"
//                   echo "${env.commitEmail}"
//                   echo "${env.commitName}"
//                  echo "${currentBuild.number}"
//                   echo "${env.JENKINS_URL}"
//                  echo "${env.foo}"
// //                  script {
// //                 //  welcomeJob()
// // //                  echo "${env.foo}"
// //                  }
// //                  echo "${env.foo}"
//                }
//            }
//           stage("Checking") {
//               steps {
//                    echo "checking"
//                }
//            }
           
           
//            stage("Running Testcase") {
//               steps {
//                    echo "completed"
//                }
//            }
           
//        }
//    }