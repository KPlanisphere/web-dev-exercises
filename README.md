# Web Development Exercises

## Repository: web-dev-exercises

### Description

This repository contains various exercises completed as part of learning HTML, CSS, and basic web design. Each exercise focuses on different aspects of web development, from embedding styles to creating structured layouts. The exercises demonstrate the application of HTML tags and basic CSS styling.

### Project Structure

- **Exercise 1: Calendars**
  - **Files:**
    - `Calendario (LINEA).html`: HTML file using inline styles to create a calendar.
    - `Calendario (EMBEBIDO).html`: HTML file using embedded styles to create a calendar.
    - `Calendario (ARCHIVO).html`: HTML file using an external CSS file for styling.
    - `CalendarioStyle.css`: External CSS file used for styling the calendar in `Calendario (ARCHIVO).html`.

  - **Description:**
    - These files demonstrate the creation of a calendar for the year 2023 using different styling techniques. The `Calendario (LINEA).html` file uses inline styles, `Calendario (EMBEBIDO).html` uses embedded styles, and `Calendario (ARCHIVO).html` uses an external stylesheet.

- **Exercise 2: Rubik's Cube**
  - **File:**
    - `Rubik.html`: HTML file that represents a Rubik's Cube using tables and embedded styles.

  - **Description:**
    - This exercise focuses on using tables to create a visual representation of a Rubik's Cube. It includes different colored cells to mimic the cube's appearance and demonstrates the use of embedded styles.

- **Exercise 3: Annual Sales Report**
  - **File:**
    - `Ventas Anuales.html`: HTML file that presents an annual sales report using tables and embedded styles.

  - **Description:**
    - This exercise showcases the use of tables to display data in a structured format. The file includes a summary of annual sales across different branches, comparing data from 2020 and 2021, and highlights differences in performance.

### Notable Code Snippets

#### Calendario (LINEA).html
Inline styles are used to create and style the calendar.

```html
<div align="center" style="background-color: #003b5c; color: white;">
    <header>
        <h1>EXAMEN PRACTICO UNIDAD 2: CALENDARIO USANDO ESTILOS EN LINEA</h1>
    </header>
</div>
<h1 style="color: #262626; font-size: 400%;">CALENDARIO 2023</h1>
```

#### CalendarioStyle.css

External CSS file used for styling the calendar.

```css
.bold { font-weight: bold; }
.header { text-align: center; background-color: #003b5c; color: white; }
.titulo { text-align: center; color: #262626; font-size: 200%; }
/* Additional styles for various background colors and text colors */
```

#### Rubik.html

Embedded styles are used to create the Rubik's Cube visual.

```html
<style> .header { text-align: center; background-color: #003b5c; color: white; }
    .rubik { text-align: center; background-color: black; }
    .ficha td { width: 100px; height: 100px; } </style>
<table align="center" border="4" cellspacing="2" class="rubik ficha">
    <tr><td class="amarilloBG"></td><td class="amarilloBG"></td><td class="cafeBG"></td></tr>
    <!-- Additional rows to complete the Rubik's Cube -->
</table>
``` 

#### Ventas Anuales.html

Displays a structured table for the annual sales report with embedded styles.

```html
<style> .header { text-align: center; background-color: #003b5c; color: white; }
    .centerGeneral { text-align: center; }
    .azulBG { background-color: #5c97f7; }
    .rojoTXT { color: #b80000; } </style>
<table border="2" align="center">
    <tr class="blancoTXT bold azulBG">
        <th>TOTAL SUCURSALES</th><th>GANANCIAS AÑO 2020</th><th>GANANCIAS AÑO $ 2021</th><th>DIFERENCIAS</th>
    </tr>
    <tr class="azulClaroBG">
        <td>50</td><td>$1,456,234,556.56</td><td>$1,246,704,344.12</td><td class="rojoTXT bold">-$209,530,212.44</td>
    </tr>
</table>
 ```

### Setup and Usage

1.  **Clone the Repository:**
    
	```sh
    git clone https://github.com/KPlanisphere/web-dev-exercises.git
    cd web-dev-exercises
    ```
    
2.  **Open the HTML Files:**
    
    -   Open any of the HTML files in your preferred web browser to view the exercises.