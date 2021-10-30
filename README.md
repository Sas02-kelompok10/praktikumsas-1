# praktikumsas-1
kelompok 10
# modul 1 virtualisasi
## case study
---
- vm.local
  - berisi landing page
- vm.local/blog
  - berisi blog
- vm.local/app
  - berisi aplikasi perusahaan
  
## skema
---
- virtual box ubuntu server IP : 192.168.120.100
- LXC debian server 9 php5.6 IP : 10.0.3.103
- LXC ubuntu server 18.04 php5.6 IP : 10.0.3.102
- LXC ubuntu server 16.04 IP : 10.0.3.103

##problem solving
---
- **memastikan bridge adapter dan set ip static**
- ![image](https://user-images.githubusercontent.com/93419670/139521916-43e63902-34be-49c4-8775-ea99827c9544.png)
- **ubah ip ubuntu landing**
- ![image](https://user-images.githubusercontent.com/93419670/139522064-89929f87-7add-41ce-9ec8-5d7daf02347c.png)
- **restart ip,lalu cek ip dengan ifconfig**
- ![image](https://user-images.githubusercontent.com/93419670/139522111-384922f9-5d7a-4bca-b5f4-028e379eb932.png)
- **cek koneksi internet dengan ping 1.1.1.1 / google.com / 8.8.8.8**
- ![image](https://user-images.githubusercontent.com/93419670/139522160-ff79a8c9-c5b1-49bf-bc53-c107be6a84a2.png)
- **install LXC debian**
- ![image](https://user-images.githubusercontent.com/93419670/139522182-9306677d-2f56-4015-8615-1908f5396711.png)
- **cek LXC debian**
- ![image](https://user-images.githubusercontent.com/93419670/139522213-fe18d644-7a70-4484-9d8c-b1b6e82bb833.png)
- **start LXC debian**
- ![image](https://user-images.githubusercontent.com/93419670/139522228-cdbbfab3-1d8a-4263-bc37-39ba9f7ac40e.png)
- **install nginx dan nginx extras**
- ![image](https://user-images.githubusercontent.com/93419670/139522259-941a0463-50da-4605-a2b2-22c798715be4.png)
- **set ip static debian php**
- ![image](https://user-images.githubusercontent.com/93419670/139522300-fb15c843-d3c3-4608-9bf6-84a19d9093cc.png)
- **restart settings dan cek ip**
- ![image](https://user-images.githubusercontent.com/93419670/139522324-f47830fa-5826-4eb2-969b-b83c1e4f79dc.png)
- **setting nginx**
- ![image](https://user-images.githubusercontent.com/93419670/139522344-02882a82-ee48-4176-b954-d953e75c2ec4.png)
- ![image](https://user-images.githubusercontent.com/93419670/139522360-a975e18f-9b0d-4ee5-bb28-22af47c97655.png)
- ![image](https://user-images.githubusercontent.com/93419670/139522397-441f1127-5b80-4a7e-b323-3ac733f1c030.png)
- ![image](https://user-images.githubusercontent.com/93419670/139522412-bfd3d383-ee80-4286-a4f9-4d1741e2e952.png)
- ![image](https://user-images.githubusercontent.com/93419670/139522429-dc76ab87-79f0-450e-9aff-8d2e11a050a4.png)
- ![image](https://user-images.githubusercontent.com/93419670/139522443-e24e1997-262d-4243-87d7-6f72e2367989.png)





