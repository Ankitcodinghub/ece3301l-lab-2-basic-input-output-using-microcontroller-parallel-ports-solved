# ece3301l-lab-2-basic-input-output-using-microcontroller-parallel-ports-solved
**TO GET THIS SOLUTION VISIT:** [ECE3301L LAB 2-Basic Input/Output using Microcontroller parallel ports Solved](https://www.ankitcodinghub.com/product/ece3301l-lab-2-basic-input-output-using-microcontroller-parallel-ports-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91502&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE3301L LAB 2-Basic Input\/Output using Microcontroller parallel ports Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
LAB2

Basic Input/Output using Microcontroller parallel ports

To perform the lab below, you need to download the spec of the processor PIC18F4620 that we are using in the lab. Go to the following link:

http://ww1.microchip.com/downloads/en/devicedoc/39626e.pdf

Remember that this processor is an upgrade to the processor PIC18f4321.

Download the datasheet and save somewhere (like Desktop) that you can easily have access to it.

MA TERIALS:

Provided by instructor:

<ul>
<li>3 RGB LEDs</li>
<li>(4) regular LEDs (any color)</li>
<li>1 bank of 4 minimum DIP Switches
Student must get the following:
</li>
</ul>
• (4) 1K or higher resistors

PART 1)

Write a program that will input from a bank of 4 switches (DIP switches) and output each corresponding input to an equivalent LED. There would be a total of 4 LEDs. The input switches are connected from PORT A bits 0-3 while the output LEDs are tied to PORT B bits 0-3.

Hint:

a) Use the downloaded datasheet of the PIC18F4620, go to chapter 9 ‘I/O Ports’. Study the definitions of the TRISx registers where ‘x’ represents the PORT name. Set the right value of each bit in the TRIS register to setup whether the corresponding pin is an input or output. A ‘1’ will make the pin an input while a

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
‘0’ makes it an output. Reading something from a switch to a pin of a port will make that pin an input. Controlling a LED from a pin of a port will make that pin an output. Based on those definitions, you should be able to determine what port should be setup as an input port or an output port. From there, you should be able to figure the value to be placed into the TRISx registers. In this case, you should deal with the registers TRISA and TRISB.

<ol start="2">
<li>b) &nbsp;If you use PORTA or PORTB for the inputs and/or outputs, you need to study the definitions of the register ADCON1 (see the chapter 19 ’10-bit Analog-to-Digital Converter A/D Module’ in the datasheet) and its PCFG3:PCFG0 bits. You need to make sure that the pins from ports A and B are setup in digital mode and not analog meaning all the pins must be digital.</li>
<li>c) &nbsp;Write an endless loop to read the input switches and output the values to the LEDs. Based on the schematics shown on ‘LAB2_Schematics.pdf’, the four inputs should be port B bits 0 through 3 while the four LEDs should be connected to port A bits 0 through 3.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
Example:

void main() {

char in;

TRISA = 0x??; TRISB = 0x??; ADCON1 = 0x??;

while (1) {

</div>
<div class="column">
// Use variable ‘in’ as char

// fill out the ?? with the proper values // fill out the ?? with the proper values // fill out the ?? with the proper values

// read data from PORTA and save it

// into ‘in’

// Mask out the unused upper four bits // Output the data to PORTB

</div>
</div>
<div class="layoutArea">
<div class="column">
} }

PART 2)

</div>
</div>
<div class="layoutArea">
<div class="column">
in = PORTA;

in = in &amp; 0x0F; PORTB = in;

</div>
</div>
<div class="layoutArea">
<div class="column">
Connect the provided Common-Cathode RGB LED at D1 to the pins RC0 through RC2. Pin RC0 will be used to turn on the RED color of LED D1, RC1 is for the GREEN and RC2 is for the BLUE.

Write an endless loop where the lowest three pins of the DIP Switch SW1 (pins connected to port A bits 0 through 2) are read and then these three bits are outputs to the port C whereas the following color will be generated on the LED D1:

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Inputs (SW1)

RA2 RA1 RA0 000 001 010 011 100 101 110 111

</div>
<div class="column">
Outputs (D1)

RC2 RC1 RC0 Color

0 0 0 Nolight 001Red 010Green 011Yellow 100Blue 101Purple 110Cyan 111White

</div>
</div>
<div class="layoutArea">
<div class="column">
Don’t forget to add the TRISC command for this port C in your code.

Show the operation of this part by changing the switch settings of SW1 and check that the color of the RGB LED D1 matches with the combination of the switch. Make sure that the most significant bit of SW1 is on the left side of that switch and the LSB is on the right side.

PART 3)

Write an endless loop that will continuously generate the list of colors shown on Part 2) with about 1 second delay between each color. There is no input to read.

Hint:

Write the subroutine Delay_One_Sec() below:

void Delay_One_Sec() {

for(int I=0; I &lt;17000; I++); }

Once this delay routine is written, use it to generate the time delay. You would need an overall endless loop that will output the 8 different colors spaced by 1 second delay. To achieve this task, you will need to add a FOR loop with an 8-count value (count from 0 to 7). Use the counter value as the color of the output to be generated. In the FOR loop, after you have output the color to the port C, add the Delay_One_Sec() routine to wait 1 second. Failure to have this delay will cause the colors to be generated at a very high rate so that your eyes cannot differentiate.

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
PART 4)

Based on the code on Part 3), add another Common-Cathode RGB D2 to the PORT D bits 0 through 2. Don’t forget to add the TRISD command for this port D in your code.

Take the code from part 3) and add the needed coded to generate the colors for the LED D2. Notice the pattern of the colors for D2 with respect to the ones for D1 so that there is a simple formula to generate those colors for D2.

</div>
</div>
<div class="layoutArea">
<div class="column">
Step #

0 1 2 3 4 5 6 7

PART 5)

</div>
<div class="column">
Color @RGB LED D1

No light (off) Red

Green

Y ellow

Blue Purple Cyan White

</div>
<div class="column">
Color @RGB LED D2

White

Cyan

Purple

Blue

Y ellow Green

Red

No light (off)

</div>
</div>
<div class="layoutArea">
<div class="column">
Now, this part will add another RGB LED D3 to Part 4. D3 has its three pins connected to PORTD bit 5 through 7. Here are the sequence of colors for the LEDs D1, D2 and D3.

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="0">
<li>0 &nbsp;No light (off)</li>
<li>1 &nbsp;Red</li>
<li>2 &nbsp;Green</li>
<li>3 &nbsp;Y ellow</li>
<li>4 &nbsp;Blue</li>
<li>5 &nbsp;Purple</li>
<li>6 &nbsp;Cyan</li>
<li>7 &nbsp;White</li>
</ol>
</div>
<div class="column">
Cyan

Y ellow Purple

Green

No light (off) White

Red

Blue

</div>
<div class="column">
Purple

Red

No Light (off) Blue

Cyan

Y ellow

Green

White

</div>
</div>
<div class="layoutArea">
<div class="column">
Due to the random assignments of the colors for D2 and D3, I suggest the use of an array to contain the proper values.

General reminder:

Make sure that for this lab create a general folder marked as ‘lab2’. From there, create sub-folders one for each part. Since we are going to have five parts, then we should have five sub-folders marked for example lab2p1, lab2p2, … lab2p5.

</div>
</div>
</div>
