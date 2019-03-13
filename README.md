# scp
ubuntu scp
1.check your ubuntu whether to have ssh
'''
pe -ef | grep "ssh"
'''

2.if not ,install ssh
'''
sudo apt-get install ssh
'''

3.check the client IP:
'''
ifconfig -a
'''

#[image](https://github.com/zhucheng725/scp/blob/master/client.png)
inet addr:172.19.133.160

4.send files to the client:
'''
$ sudo scp filename_path_on_host client@IP:save_path
'''

'''
$ sudo scp /media/zhu/0003E52A000920B8/procedure/tx2/tf_trt_models.tar.gz    nvidia@172.19.133.160:home/nvidia/procedure/trt_models/
'''
#[image](https://github.com/zhucheng725/scp/blob/master/host.png)
