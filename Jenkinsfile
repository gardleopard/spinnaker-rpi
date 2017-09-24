
node { 
    git branch: 'build_spinnaker_components', url: 'https://github.com/gardleopard/spinnaker-rpi.git'
    sh "$WORKSPACE/script/build"
}
node { 
    git  url: 'https://github.com/spinnaker/igor.git'
    sh "/bin/ls"
}



