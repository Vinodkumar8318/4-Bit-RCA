# TAPEOUT PROCESS

### 1) CREATING A REPOSITORY
  Create the reposiory by reffering th below github
  
    - https://github.com/efabless/caravel_user_project


### 2) CLONING AND SETUP
 Go to terminal and folloe the below commands
 
     - git clone https://github.com/Vinodkumar8318/4-Bit-RCA-Tapeout.git
     - mkdir ~/asic  
     - export OPENLANE_ROOT=~/asic/openlane
     - export PDK_ROOT=~/asic/pdk
     - cd 4-Bit-RCA-Tapeout
     - make setup

![Screenshot from 2023-11-24 15-02-14](https://github.com/Vinodkumar8318/4-Bit-RCA-Tapeout/assets/142583979/1cfbe9b5-2b7e-4e4a-918d-0257efc87b6b)

     - ls openlane/
     - make user_proj_example

![Screenshot from 2023-11-24 17-32-01](https://github.com/Vinodkumar8318/4-Bit-RCA-Tapeout/assets/142583979/eaf17166-8aeb-41c4-b390-6e1f499be20b)

     - ls gds/
     - After completed successfully check the project name wll be updated with gds.
     - klayout gds/user_proj_example.gds

![Screenshot from 2023-11-24 17-35-43](https://github.com/Vinodkumar8318/4-Bit-RCA-Tapeout/assets/142583979/31f41b7b-cf3f-4a10-8bc4-504c63a57c4b)




