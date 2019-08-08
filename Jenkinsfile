node {
    stage('Ready') {
        step {
            powershell 'Write-Output "Step1"'
        }
        
        step {
            powershell 'Write-Output "Step2"'
        }
    }

    stage('Build') {
        powershell 'Write-Output "Build Start"'
    }
    
    stage('Test') {
        powershell 'Write-Output "Test Start"'
    }

    stage('Deploy') {
        powershell 'Write-Output "Deploy, Start!"'
    }
}

