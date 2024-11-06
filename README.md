# Storm OS

![Storm photo](https://arc-anglerfish-washpost-prod-washpost.s3.amazonaws.com/public/YKXZVKJ37FD6BIQWJU6PBDZCKM.jpg)


## What is Storm OS?
*This will probably be my pet-project lightweight OS based on own and/or Linux system kernel.*
*Code based on [this](https://www.youtube.com/watch?v=FkrpUaGThTQ&list=PLZQftyCk7_SeZRitx5MjBKzTtvk0pHMtp) tutorial*

#### Prerequirements
  1. Install [qemu](https://www.qemu.org/)

#### Build on Mac: 
  1. docker build buildenv -t my-os-kernel-buildenv  
  2. docker run --rm -it -v $(pwd):/root/env my-os-kernel-buildenv
  3. make build-x86_64
  4. exit from container
  5. qemu-system-x86_64 -cdrom dist/x86_64/kernel.iso  



## Remember - Hope dies last :v:
