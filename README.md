**DROVNI** is a flying robotic platform for education, research and real world applications. **DROVNI** is Ingeniarius’ flying solution for both indoor and outdoor experiments. Due to the relation between its low cost and outstanding features, this fully-featured unmanned aerial vehicle depicts a wide range of applications, such as exploration, surveillance, networked robotics, remote sensing and many others.

# 1.	Install
To extend **DROVNI**’s sensing functionalities, you must first connect to it and program it. **DROVNI** comes with ARM CPU BeagleBone Black (BBB) controller so, to program it, you can simply follow the steps in http://beagleboard.org/getting-started. Once connected to the BBB through SSH, use the following login:
* username: ubuntu
* password: temppwd

For instance, the user can gain access to the installed camera (videodevice /dev/video0) through the BBB and use it for surveillance purposes (e.g., remote sensing). **DROVNI**’s BBB uses the [Motion package](https://launchpad.net/ubuntu/trusty/+package/motion), which supports motion detection. **DROVNI**’s streaming video can be accessed directly through the network as http://BBB_IP:8081.

That's it - Enjoy!
