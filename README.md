# Jfrog_Integration_Jenkins
wget https://releases.jfrog.io/artifactory/artifactory-rpms/artifactory-rpms.repo -O jfrog-artifactory-rpms.repo;
sudo mv jfrog-artifactory-rpms.repo /etc/yum.repos.d/;
sudo yum update && sudo yum install jfrog-artifactory-oss
