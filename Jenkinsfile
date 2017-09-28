
stage('core') { 
  build 'spinnaker'
  build 'clouddriver'
  build 'front50'
  build 'orca'
}

stage('extras') {
  build 'igor'
  build 'echo'
  build 'gate'
}

stage('frontend') {

  build 'deck'
  build 'publish repo'
}

