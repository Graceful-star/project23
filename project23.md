# DOCUMENTATION OF PROJECT 23

1. I updated my pod manifest file and applied it

![Project23](images/image1.PNG)

2. I checked the pods, Exec into one of the running pods and I checked the default configuration file

   ![Project23](images/image2.PNG)
   ![Project23](images/image3.PNG)

 3. I checked the node that is running the pod and used the ip address to check the availability zone

    ![Project23](images/image4.PNG)  
    ![Project23](images/image5.PNG)
    ![Project23](images/image6.PNG)

4. I created a volume in the same availability zone

   ![Project23](images/image7.PNG)

5. I updated the POD manifest file and applied it. Then I checked the pods

    ![Project23](images/image8.PNG)

6. I checked the storageclass and I realized that the VolumeBindingMode is "waitforfirstconsumer" which has not been created.

    ![Project23](images/image9.PNG)

7. So I created a file for the persistent-volume-claim and I applied it

     ![Project23](images/image10.PNG)

 8. I checked the pvc, updated the file again and applied it

     ![Project23](images/image11.PNG) 
     ![Project23](images/image12.PNG)
     ![Project23](images/image13.PNG)
     ![Project23](images/image14.PNG)
     ![Project23](images/image15.PNG)

9. I exec into the running container and I copied the content of the index.html file

    ![Project23](images/image16.PNG)

10. I created a config-map.yaml manifest file and a deployment manifest file, then I applied it

      ![Project23](images/image17.PNG)
      ![Project23](images/image18.PNG)

11. I checked the pods and exec into the running pod. Then I checked the cm too


   ![Project23](images/image19.PNG)

12. I edited the website-index-file with my PC's editor and I restarted the deployment

   ![Project23](images/image20.PNG)

13. I checked the pods and ran a port-forward command
    
    ![Project23](images/image21.PNG)

14. Then I accessed the port on my browser

    ![Project23](images/image22.PNG)




