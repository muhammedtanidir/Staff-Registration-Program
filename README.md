# Staff-Registration-Program
You can register your staff to SAP database tables with this program.
In this program gives you just a short example for registration staff to database table.
The Program description are below:
- Create a new package and request via SE80 and SE10 transaction codes.
- Create domain and data element for variables which are you need in the table via SE11 transaction code.
- Create Database Table via SE11 transaction code.
- Add that variables with their data element in the database table via SE11 transaction code.
- Create a Message Type via SE91 and use insede the program.
- Create a program with Top include via SE80 using with your package and request.
- Create a screen and open it's BPO and PAI modules.
- Create a Gui Status and define Back button as a exit command.
- Create Transactions and set screen number inside.
- Open layout part and design interface.
- Write program codes and check it with debug process.
- (in that program I used subroutines, alv grids, inclules, screens, gui status and transactions ).
-   *Personel TCKN lenght must be 11 else program shows allert message.
-   **Age Must be between 18-99 that's why program gives you allert if you set birth date value more then 100 years old or less than 18 years old .
- Check your Database table via SE16N transaction code.
- Secreen Shots are Below:
<img src="https://github.com/muhammedtanidir/Staff-Registration-Program/blob/main/pkyt_program_ss.JPG?raw=true" align="center" />
<img src="https://github.com/muhammedtanidir/Staff-Registration-Program/blob/main/pkyt_program_screen_layout.JPG?raw=true" align="center" />
<img src="https://github.com/muhammedtanidir/Staff-Registration-Program/blob/main/pkyt_flowss.JPG?raw=true" align="center" />
<img src="https://github.com/muhammedtanidir/Staff-Registration-Program/blob/main/pkyt_mainss.JPG?raw=true" align="center" />
<img src="https://github.com/muhammedtanidir/Staff-Registration-Program/blob/main/pkyt_screenss.JPG?raw=true" align="center" />
<img src="https://github.com/muhammedtanidir/Staff-Registration-Program/blob/main/pkyt_database_table.JPG?raw=true" align="center" />
<img src="https://github.com/muhammedtanidir/Staff-Registration-Program/blob/main/pkyt_tabless.JPG?raw=true" align="center" />
<img src="https://github.com/muhammedtanidir/Staff-Registration-Program/blob/main/pkyt_display_alv.JPG?raw=true" align="center" />
