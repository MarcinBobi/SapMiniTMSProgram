# SapMiniTMSProgram

Road Transport Order Management System in SAP ABAP – MINITMS Dialogue Application Project
Diploma thesis

The aim of this thesis was to design and implement a system for managing road transport orders in the SAP environment, using classic dialogue programming in ABAP – an application called MINITMS (Mini Transportation Management System).
The project discussed the theoretical foundations of SAP ABAP technology, including the principles of dialogue programme design, good coding practices (e.g. Clean ABAP), as well as a brief overview of SAP functionality in the area of transport management (SAP TM). On this basis, an application was created with the following main features:
- Registration, editing and deletion of transport orders,
- Main data management: customers, logistics locations, vehicles and drivers,
- User interface based on SAP GUI and ALV (data grids) screens,
- Automatic generation of unique order numbers,
- Ability to send an e-mail with order information to the driver,
- Direct integration with the SAP database: transparent tables, ZFM* function modules.
  
The application architecture has been designed in accordance with the principle of layer separation:
- Data (Z* tables),
- Application logic (FORM routines, ZFM functions),
- User interface (dynpro, PBO/PAI, ALV, tabstrips).
  
Functional tests have shown that the programme meets the specified business requirements — it is stable, intuitive and corresponds to the typical work cycle of a forwarding agent in a transport company.
