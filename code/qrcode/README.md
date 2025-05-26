# Manual

<img align="right" width="200" height="200" alt="A vehicle with the number plate 'AB 123 CD'" src="../images/plate_AB123CD.jpg">

This LaTeX code generate the QR codes of the licence plates of the cars. You can use your favourite LaTeX IDE or also online compiler and download the results as PDF to print.

> [!IMPORTANT]
> Before compiling you have to sobstitute `AB123CD` with the real licence plate of the car.
>
> **From:**
> 
> ```TeX
> \def\QRtext{AB123CD}          % Text
> ```
>
> **To:**
>
> ```TeX
> \def\QRtext{EF456GH}          % Text
> ```

So, Before compiling you have to substitute in row 9 (as shown following) the text which produces the QR-code with the licence plate of each vehicle.

This is useful to avoid remembering the licence plate of each vehicle (and, in this way, it is more difficult to make mistakes, e.g. by the spellchecker of the mobile phone).

> [!TIP]
> You can change the logo in the middle, e.g.
>
> **From:**
> 
> ```TeX
> \def\QRimage{logo.svg}        % Image
> ```
>
> **To:**
>
> ```TeX
> \def\QRimage{logo_no_scritta.svg}        % Image
> ```
