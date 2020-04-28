# cloud-scanner-mobile

docker pull bitriseio/docker-android
alias cordova='docker run -it --rm --privileged -v /dev/bus/usb:/dev/bus/usb -v $PWD:/bitrise/src bitriseio/docker-android:latest cordova'

docker build