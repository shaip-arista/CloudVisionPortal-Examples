# EST Enrollment using studio
 This example studio and action package can be used to generate the necessary EOS configuration for EST protocol.
 
Prerequisite:
 1. Download CA certificate of the EST and Radsec to local directory
 2. intstall into cvaas the latest certificate_management_x.y.z.tar
 3. Use the certificate_management to create a self signed certificate for each switch.
 4. Use the certificate_management to push both EST & Radsec CA certificate into each switch (directory "certificate:").
 5. ** Prerequisites can be done using the provided custom actions "certificate_management"

How to use this studio:
1. Fill in the information used to generatae the auto-certficaite using EST protocol.
2. Optionally: Fill the Radsec information to generate general dot1x/radsec config using the auto generated certificate.

 
 
