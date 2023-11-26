# he-simulation
### A simple Heat Exchanger simulation app written in Scilab 6

![window preview](https://github.com/Danedevz/he-simulation/blob/main/preview/Window.png?raw=true)

#### Required data:
- path/directory leading to your *.xls* file consisting of input mass flow and heat capacity parameters (CP) for each component (ex: *C:\Users\path\to\file.xls*)
- Make sure your data located at sheet 1, starting from A1
<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky" rowspan="2">Component</th>
    <th class="tg-0lax" rowspan="2">Mass In</th>
    <th class="tg-0lax" colspan="5">Cp</th>
  </tr>
  <tr>
    <th class="tg-0lax">A</th>
    <th class="tg-0lax">B</th>
    <th class="tg-0lax">C</th>
    <th class="tg-0lax">D</th>
    <th class="tg-0lax">E</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">component1_name</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
  </tr>
  <tr>
    <td class="tg-0pky">component2_name</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
  </tr>
  <tr>
    <td class="tg-0lax">component3_name</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
  </tr>
  <tr>
    <td class="tg-0lax">component4_name</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
    <td class="tg-0lax">...</td>
  </tr>
</tbody>
</table>

- reference temperature (K)
- T input
- T output

#### What you get:
- Cp input and output
- Enthalpy input and output
- Amount of heat required (Q)
