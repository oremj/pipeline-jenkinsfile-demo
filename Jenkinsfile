stage 'Demo'
node {
  sh 'env'
}

stage 'Demo 2'
node {
  sh 'echo foo'
}

stage 'a new branch'

node {
  20.times {
    sh "echo test multibranch ${it}"
  }
}
