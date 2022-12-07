---
####################### Banner #########################
banner:
  title : "From Idea to Circuit in the same day, Autonomously"
  image : "Renders/design_overview.png"
  content : "The Lobster is 2-layer PCB prototyping solution designed to minimize the time between idea and prototype. The goal is to eliminate downtime in the design cycle, and facilitate the same fast, iterative design approach that 3D printers provide. The lobster aims to be a low friction, plug-and-play solution which turns your circuits into physical prototypes with the press of a button, and no oversight."
  button:
    enable : true
    label : "See our Project Goals"
    link : "goals/"

##################### Feature ##########################
feature:
  enable : true
  title : "Features"
  feature_item:
    # feature item loop
    - name : "Fully Automatic"
      icon : "fas fa-robot"
      content : "Our machine is designed to be fully automatic. Just load your material and come back when your pcb is ready"
      
    # feature item loop
    - name : "Open Source"
      icon : "fas fa-code"
      content : "Every part of our project is open source, from software to mechanical design. This means anyone can access the designs to make modifications as they see fit"
      
    # feature item loop
    - name : "Web Interface"
      icon : "fas fa-wifi"
      content : "To make our machine easy to use and cross-platform, it comes with a handy web interface to control the machine from your browser"
      
    # feature item loop
    # - name : "Value For Money"
    #   icon : "fas fa-heart"
    #   content : "Lorem ipsum dolor sit amet consectetur adipisicing elit quam nihil"
      
    # # feature item loop
    # - name : "Faster Response"
    #   icon : "fas fa-tachometer-alt"
    #   content : "Lorem ipsum dolor sit amet consectetur adipisicing elit quam nihil"
      
    # # feature item loop
    # - name : "Cloud Support"
    #   icon : "fas fa-cloud"
    #   content : "Lorem ipsum dolor sit amet consectetur adipisicing elit quam nihil"
      


######################### Service #####################
service:
  enable : true
  service_item:       
    # service item loop
    - title : "Automatic Via Processing"
      images:
      - "Renders/via_pressing.png"
      - "Renders/via_pressing_arrows.png"
      - "Renders/wire_feeding.png"
      content : "The main differentiating factor between our machine and existing solutions is our novel automatic via process. Current solutions all require messy chemical processes to plate the copper vias, or intensive manual riveting (which becomes more and more prohibitive as designs grow). We have developed a via pressing process which forms solid vias using copper wire and an automatic press to handle this step automatically without mess or user interaction."
      button:
        enable : false
        label : "Check it out"
        link : "blog/process/"
        
    # service item loop
    - title : "No Tool Changes, Automatic Material Flipping"
      images:
      - "Renders/milling_heads.png"
      - "Renders/via_flipping.png"
      content : "To avoid the need for proprietary or obsucure raw materials, we chose a cnc milling process to create 2-layer pcbs from common copper-clad FR4. For the prototype, we implemented a multi-toolhead design and an automatic flipping mechanism to demonstrate a fully automated 2-layer pcb prototyping process."
      button:
        enable : false
        label : "Check it out"
        link : "blog/process/"
        
    # service item loop
    - title : "Shared Motion Carriage"
      images:
      - "Renders/design_overview.png"
      - "Renders/rear_view.png"
      content : "The milling heads and via pressing mechanism of the lobster share a motion carrriage. This allows us to automatically move between the milling and via processes without the need for user intervention"
      button:
        enable : false
        label : "Check it out"
        link : "blog/process/"
        
    # service item loop
    - title : "The Team"
      images:
      - "Team/Brandon-Hao.jfif"
      - "Team/Caleb-Brett.jfif"
      - "Team/David-White.jfif"
      - "Team/James-White.jpg"
      - "Team/Josh-Dellosa.jfif"
      content : "We are a group of 5 mechatronics engineering students from the university of waterloo, the lobster is our 4th year design project inspired by our collective desire to see better rapid prototyping solutions for PCB design. We designed this machine to service a need that we all saw, while addressing reocurring pain points we have noticed in current market solutions."
      button:
        enable : true
        label : "Learn More"
        link : "blog/team/"
        
################### Screenshot ########################
#screenshot:
#  enable : true
#  title : "Experience the best <br> workflow with us"
#  image : "images/screenshot.svg"

  

##################### Call to action #####################
# call_to_action:
#   enable : true
#   title : "Ready to get started?"
#   image : "images/cta.svg"
#   content : "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Consequat tristique eget amet, tempus eu at consecttur."
#   button:
#     enable : true
#     label : "Contact Us"
#     link : "contact/"
---
