WEEK 1 constitues of the literature survey to decide the topic and then specifying the characteristics or the constraints of the circuit to be made.

    [
![IMG_20210813_225623](https://user-images.githubusercontent.com/27013795/129400267-69b05c38-31d6-4801-b924-852b196edfd2.jpg)
](url)
    
    
    Operating modes of the IP is specified:
  [ ![IMG_20210813_225639](https://user-images.githubusercontent.com/27013795/129400648-89fbc015-28b4-4efd-9024-23240cf02ae8.jpg)
  ](url)
    
    Application of the IP is specified:
  [ ![IMG_20210813_225655](https://user-images.githubusercontent.com/27013795/129397487-61f15b24-b093-4635-bae3-3058cf5c559b.jpg)
    ](url)
    
    Rectification of the errors given in the feedback.
  [ ![IMG_20210813_225711](https://user-images.githubusercontent.com/27013795/129397942-1f0c09ca-5daf-4ead-ad51-c92330bed795.jpg)
    ](url)

WEEK 2 constitutes of the making of the verilog file of the IP:
    
    RTL Code and the Testbench:
  [  [rtl codetb.pdf](https://github.com/Dhatrish1/4-BIT-CARRY-LOOKAHEAD-ADDER/files/6984235/rtl.codetb.pdf)
    ](url)
    
    Waveforms:
  [ ![image](https://user-images.githubusercontent.com/27013795/129398198-95c9217f-c65c-4613-98fc-5adea6579d4a.png)
    ](url)


WEEK 3 constitutes of the download and installation of the different tools:

    
    Steps to install Different open source tools and run on UBUNTU:
        
        1) sudo apt-get install git
        2) git clone https://github.com/kunalg123/vsdflow.git
        3) cd vsdflow
        4) chmod 777 opensource_eda_tool_install.sh
        5) ./opensource_eda_tool_install.sh 
        6) ./vsdflow spi_slave_design_details.csv
        7) ./vsdflow picorv32_design_details.csv
        
    List of Tools installed:

        1) Yosys - RTL Synthesis
        2) blifFanout - High fanout net (HFN) synthesis
        3) graywolf - Placement
        4) qrouter - Detailed routing
        5) magic - VLSI Layout tool
        6) netgen - LVS
        7) OpenTimer and OpenSTA - Static timing analysis tool
        
        
    Steps to install Openlane and pdks:
        
        git clone https://github.com/The-OpenROAD-Project/OpenLane.git --branch 2021.08.03_05.51.29
        Comment line number 93 in Makefile.
        Then
        make openlane
        make pdk
        make test


