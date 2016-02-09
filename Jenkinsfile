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
  for (i = 0; i < 20; i++) {
    sh "echo test multibranch ${i}"
  }
}
