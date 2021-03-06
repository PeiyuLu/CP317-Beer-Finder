# CP317 Beer Finder Web App

## Inspiration:
Inspiration:
Have you ever had an idea of what kind of beer you wanted, maybe a dark yellow beer with a medium body and an approximately 5% alcohol content, but you didn’t know what brand would be best linked to your criteria? 

Our web application hopes to solve this by asking for user search criteria and returning a list of beers that match their specifications in order from ***most alike*** to ***least alike***.

## Tools:
#### Front-end:
* **Scripting:** Django templating language (DTL) / JavaScript
* **Structure:** HTML
* **Styling:** CSS / Bootstrap

#### Back-end:
* **Server:** Django
* **Database:** PostgreSQL (built-in with Django)
* **API:** Django GET and POST definitions for accessing/modifying database content
* **Data Structures:** List, Queue, Stack
* **Testing:** PyTest

#### Connection between Front and Back-ends:
* Django has a templating system called Jinga which allows for the dynamic conditional rendering of HTML files
* All CSS and JS files are contained in a special folder named *static* where they can be referenced within the HTML file
* Django is responsible for hosting the web application, accessing and modifying our PostgreSQL database, and with the Django REST Framework extension, it can handle API requests so the front-end client can access/modify data from our back-end
* JS is responsible for further manipulation of the HTML Document Object Model (DOM) that cannot be handed by DTL
* CSS and Bootstrap are used for styling

## Team Members
### Lead Developers
- Russell Goldman
- Tauqeer Choudhry
- Don Vo

### Django Templates
- Abdullahi Abdullahi
- Ziheng Wang (Isaac)
- Zhixian Li (Catherine)
- Abdisalan Mohamed Abdi

### Bootstrap / CSS Styling 
- Ni Yang (Nina)
- Yuting He
- Franchesco Livado

### Modellers and Database
- Yanda Tao
- David Moreno
- Sirong Liu
- Yu He
- Peiyu Lu (Lucy)

### Views and Routing
- Abraham Banka
- Zizheng Huang
- Mengdan Wan
- Jerry Haq

### API Developers
- Jeremy Lickers
- Matthew Wong
- Huai Yao Hu (Walter)
- Wen Han

## Installation:
To run the program, you will need to unfreeze the virtual environment from the requirements.txt file and install it on your local system. To do so, enter the following in the terminal.
```shell
pip3 install -r requirements.txt
```
