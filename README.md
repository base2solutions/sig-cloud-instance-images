# CentOS Cloud SIG image repository.

Images are generated from kickstart scripts in the [sig-cloud-instance-build](https://github.com/CentOS/sig-cloud-instance-build/) repository.

To create any base image, go to the corresponding OS version of branch, cd into the folder that's containing dockerfile, and run 
`docker build -t <repo full path> . `
