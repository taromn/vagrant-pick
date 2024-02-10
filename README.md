# vagrant-pick
maximize vagrant's potential  
you can `up, halt, ssh` VM by just typing "vap"  

<img width="683" alt="Screenshot 2024-02-10 at 17 31 05" src="https://github.com/taromn/vagrant-pick/assets/54003207/c8c5251f-4ada-451d-b0b4-4cf442ed6de2">

# preparation
1. put the "vap" script into your directory
2. set the path  
`PATH=$PATH:<path-to-vap>`

# how to use
just type "vap"  

1. you can select VM  

  `1234567  default virtualbox running /Users/taro/vagrant/vm1`  
  `> abc1234  default virtualbox running /Users/taro/vagrant/vm2`  
  `1234abc  default virtualbox running /Users/taro/vagrant/vm3`

2. then select `up` OR `ssh` OR `halt` !  

`> halt`  
`> ssh`  
`> up`  
`what do you wanna do with host: abc1234` 
