node('jump'){
    stage("codecheckout"){
        git credentialsId: '57a01d48-9e37-411c-80fc-35f47e8b7d10', url: 'https://github.com/parthukaipa/jump.git'
    }
    stage("copy"){
        //sh"ssh $user@$serverip sudo chown -R suresh:root /opt/"
        sh "scp -r /root/workspace/tomcat $user@$serverip:/opt/test"
    }
    
}
