![OpenCV_Logo_with_text_svg_version](https://github.com/ANSHPG/Digit-Image-Generation/assets/132222062/dfcf7691-f4d2-40cd-bad6-41856b92ebae)# Digit-Image-Generation

![GENERATED-IMAGE](https://github.com/ANSHPG/Digit-Image-Generation/assets/132222062/c40aba95-e05c-43c4-b889-4c5723d304cd)

This project, developed by Anshuman Pattnaik, explores image processing techniques using Python libraries such as pandas, numpy, matplotlib, and cv2 (OpenCV). The primary objective of the project was to delve into image processing with a focus on creating a unique dataset and algorithm for image generation.

Inspiration:
The project's inspiration stemmed from a desire to explore image processing independently, rather than relying on external algorithms and APIs. Initial exploration led to YouTube videos focused on digit recognition, but the decision was made to develop a custom solution from scratch.

Dataset Creation:
The dataset comprises 16 variations of the digit 8 sourced from an image found online. Each variation was extracted as a 48x48-pixel image, forming the basis of the dataset.
![digit_final](https://github.com/ANSHPG/Digit-Image-Generation/assets/132222062/de627a94-5342-488b-9a70-e2d2af81d6f3)

Understanding Image Processing with cv2:
![Uploa<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">
<svg xmlns:svg="http://www.w3.org/2000/svg" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" viewBox="0 0 600 739" height="739pt" width="600pt">
	<defs>
		<!-- <font-face font-family="Eurostile Bold">
			<font-face-src>
				<font-face-name name="Eurostile Bold"/>
				<font-face-uri xlink:href="http://xfont.ru/fonts/3/5/1/3517.ttf">
					<font-face-format string="truetype"/>
				</font-face-uri>
			</font-face-src>
		</font-face>
		<style type="text/css">
			<![CDATA[
				@font-face {
					font-family: 'Eurostile Bold',
					src: src: local('Eurostile Bold'),
					url('http://xfont.ru/fonts/3/5/1/3517.ttf');
				}
			]]>
		</style> -->
		<path d="M -69.6503905 120.638015113  A 139.300781 139.300781 120 1 1 +69.6503905 120.638015113  L 27.7089845 47.9933689801  A 55.417969 55.417969 120 1 0 -27.7089845 47.9933689801  L -69.6503905 120.638015113  Z" id="cv_element"/>
	</defs>
	<!-- paths -->
	<use xlink:href="#cv_element" x="298" y="140" fill="#ff0101" id="red"/>
	<use xlink:href="#cv_element" x="457" y="415" fill="#0101ff" id="blue" transform="rotate(180,457,415)"/>
	<use xlink:href="#cv_element" x="142" y="415" fill="#01ff01" id="green" transform="rotate(240,142,415)"/>
	<!--- text -->
	<g id="opencv_text" fill-rule="evenodd">
		<path id="O" d="
			M 42.48 587.70 C 54.27 586.64 66.19 586.65 77.92 588.33 C 85.15 589.61 92.82 591.48 98.25 596.75 C 103.94 603.10 105.34 611.92 106.59 620.05 C 108.64 636.92 108.40 654.03 106.59 670.91 C 105.38 679.15 104.19 688.05 98.79 694.75 C 92.90 700.73 84.20 702.43 76.22 703.69 C 64.44 705.16 52.49 705.50 40.66 704.32 C 32.65 703.50 24.29 702.09 17.47 697.52 C 13.06 694.72 10.69 689.78 9.08 684.99 C 5.85 675.01 5.44 664.41 5.00 654.01 C 4.95 640.27 5.21 626.39 7.89 612.87 C 9.34 606.56 11.10 599.62 16.43 595.41 C 23.94 589.96 33.49 588.64 42.48 587.70 Z
			M 44.43 606.53 C 54.42 605.73 64.62 605.49 74.50 607.43 C 78.33 608.20 82.85 610.06 83.57 614.42 C 86.57 626.69 85.87 639.47 85.99 652.01 C 85.62 660.93 85.83 670.15 82.84 678.69 C 80.23 684.30 73.12 684.76 67.76 685.58 C 57.01 686.19 45.85 686.73 35.42 683.54 C 30.61 682.27 29.09 677.11 28.35 672.78 C 26.35 659.95 27.00 646.90 27.25 633.97 C 27.78 626.72 27.69 619.20 30.30 612.31 C 33.29 607.69 39.47 607.28 44.43 606.53 Z
		" fill="#050505"/>
		
		<path id="p" d="
			M 149.77 626.78 C 156.93 622.23 165.82 621.49 174.08 622.24 C 181.79 622.90 190.35 625.52 194.48 632.62 C 199.41 641.53 199.69 652.06 200.03 662.00 C 199.81 672.22 199.62 682.89 195.40 692.39 C 192.99 698.16 187.45 701.94 181.52 703.43 C 172.44 705.66 162.46 705.90 153.71 702.28 C 148.98 700.43 145.71 696.41 143.00 692.29 C 143.00 707.86 143.00 723.43 143.00 739.00 L 123.00 739.00 C 123.01 700.34 122.98 661.67 123.01 623.01 C 129.48 622.98 135.95 622.98 142.41 623.01 C 142.19 626.99 141.97 630.96 141.86 634.95 C 144.26 632.02 146.49 628.80 149.77 626.78 Z
			M 156.28 637.22 C 161.88 636.79 167.80 636.67 173.04 638.98 C 176.36 640.41 178.11 643.92 178.70 647.32 C 180.44 656.09 180.22 665.15 179.60 674.03 C 178.98 679.39 178.12 686.33 172.22 688.41 C 165.40 690.64 157.62 690.78 150.88 688.17 C 144.61 685.53 143.88 677.94 143.26 672.05 C 142.89 663.01 142.44 653.71 144.99 644.93 C 146.34 639.95 151.52 637.59 156.28 637.22 Z
		" fill="#050505"/>
		
		<path id="e" d="
			M 223.96 626.93 C 233.79 621.88 245.30 621.70 256.09 622.21 C 265.07 622.96 275.97 624.46 280.92 633.05 C 286.50 643.42 285.59 655.62 286.37 667.00 C 268.13 667.00 249.89 667.00 231.66 667.00 C 232.30 672.87 231.54 679.20 234.50 684.58 C 237.03 688.83 242.40 689.70 246.94 689.95 C 252.55 689.99 258.59 690.45 263.76 687.84 C 266.72 685.52 266.74 681.40 267.12 678.00 C 273.52 677.99 279.92 677.99 286.32 678.00 C 286.08 684.68 285.22 692.16 279.86 696.86 C 271.81 704.08 260.29 704.83 249.99 705.03 C 240.90 704.76 231.30 704.30 223.16 699.82 C 216.57 695.93 214.47 687.94 213.31 680.90 C 211.84 670.44 211.47 659.78 212.72 649.28 C 213.74 640.99 215.97 631.24 223.96 626.93 Z
			M 235.65 639.66 C 241.11 636.34 247.87 637.01 254.00 637.10 C 257.80 637.51 262.43 637.73 264.90 641.09 C 267.42 645.24 266.97 650.32 266.99 654.98 C 255.22 655.00 243.46 655.03 231.70 654.97 C 231.88 649.79 231.47 643.47 235.65 639.66 Z
		" fill="#050505"/>
		
		<path id="n" d=" M 328.96 626.88 C 335.88 622.08 344.82 621.41 352.96 622.35 C 359.89 623.08 367.23 625.72 371.32 631.70 C 374.95 636.66 375.96 642.98 376.01 648.99 C 375.98 667.33 376.02 685.66 376.00 704.00 C 369.66 704.01 363.33 704.01 357.01 704.00 C 356.98 686.65 357.03 669.31 356.98 651.97 C 356.79 648.18 356.94 643.80 354.09 640.88 C 351.05 637.59 346.28 636.95 342.03 636.98 C 336.89 636.95 331.33 637.83 327.37 641.38 C 323.50 644.68 322.03 650.00 322.01 654.92 C 321.98 671.28 322.02 687.64 321.99 703.99 C 315.66 704.01 309.33 704.01 303.01 704.00 C 303.00 677.00 303.00 650.00 303.01 623.00 C 309.23 622.98 315.46 622.99 321.68 623.00 C 321.65 627.74 321.18 632.45 321.04 637.19 C 323.08 633.36 325.22 629.32 328.96 626.88 Z" fill="#050505"/>
		<path id="C" d=" M 410.39 591.40 C 420.87 587.88 432.04 587.38 443.00 586.99 C 453.62 587.04 464.72 587.14 474.64 591.42 C 479.68 593.52 483.17 598.12 484.87 603.20 C 487.64 610.79 487.72 619.01 487.78 627.00 C 480.47 627.00 473.16 627.02 465.86 626.99 C 465.74 621.37 466.17 615.07 462.69 610.29 C 459.17 606.69 453.67 606.70 449.00 606.15 C 439.50 605.97 429.61 605.36 420.51 608.64 C 417.23 609.68 415.53 612.96 414.87 616.12 C 413.00 624.60 412.99 633.35 413.00 642.00 C 413.11 653.56 412.93 665.29 415.40 676.66 C 416.05 680.82 419.88 683.38 423.72 684.30 C 432.60 686.51 441.87 686.19 450.94 685.65 C 455.67 685.03 461.43 684.72 464.40 680.38 C 467.57 675.20 467.04 668.83 466.87 663.01 C 474.25 662.98 481.62 662.99 489.00 663.01 C 488.91 672.20 488.75 681.69 485.41 690.39 C 483.69 694.94 480.14 698.80 475.54 700.54 C 466.51 704.16 456.61 704.39 447.03 704.97 C 435.92 705.16 424.67 704.89 413.81 702.30 C 407.44 700.64 400.48 697.72 397.53 691.39 C 393.76 683.02 393.07 673.71 392.10 664.70 C 391.29 652.80 390.77 640.88 391.06 628.96 C 391.63 619.31 392.51 609.14 397.72 600.73 C 400.49 596.05 405.35 593.12 410.39 591.40 Z" fill="#050505"/>
		<path id="V" d=" M 492.60 588.03 C 500.22 588.04 507.84 587.82 515.45 588.14 C 522.86 611.65 531.00 634.92 538.48 658.40 C 541.39 667.42 543.45 676.70 546.46 685.69 C 549.83 675.99 551.99 665.91 555.29 656.19 C 562.60 633.48 570.11 610.84 577.41 588.13 C 584.93 587.81 592.47 588.09 600.00 587.99 L 600.00 590.48 C 587.62 628.21 575.53 666.04 563.40 703.86 C 552.08 704.09 540.74 704.12 529.42 703.84 C 517.36 665.17 504.72 626.68 492.60 588.03 Z" fill="#050505"/>
	</g>
	<!-- <text style="font-family: 'Eurostile Bold';" font-family="Eurostile Bold" font-size="170" y="95%" x="0">OpenCV</text> -->
</svg>
ding OpenCV_Logo_with_text_svg_version.svg…]()

To navigate the intricate landscape of image processing, a fundamental comprehension of cv2's functionality was imperative. Within the realm of cv2, images are typically delineated by three primary channels: Red (R), Green (G), and Blue (B). However, cv2 introduces a subtle twist by reading images in a reverse order—Blue, Green, Red (BGR). Each pixel within an image embodies a unique color code, blending varying proportions of the three channels to manifest a spectrum of colors.

Image Processing Workflow:
The project's workflow unfolds with a meticulous orchestration of image processing operations. The ensemble of images is meticulously structured into a 16-dimensional array, aptly christened 'images,' with each element representing a distinct variation of the digit 8. Characterized by dimensions of (48,48,3), each image encapsulates the nuances of its composition across three channels. Subsequently, the images undergo a transformative metamorphosis, transitioning into grayscale renditions. This metamorphosis not only serves to simplify subsequent algorithms but also mitigates the computational complexities inherent in multichannel processing. The grayscale counterparts find their abode within another 16-dimensional array, christened 'img_gray.'

Dataset Representation:
Representation of the dataset proved to be a formidable challenge, necessitating a meticulous orchestration of pixel values. Embracing a structured approach, the pixel values were methodically organized into columns, akin to the scaffoldings of a towering edifice. Each column serves as a testament to the pixel values at specific positions (0-47) across all 16 images, embodying the quintessence of their collective identity.

Mean Pixel Values and Image Generation:
The voyage culminates in the computation of mean pixel values—an emblem of collective synthesis and harmonious amalgamation. With 2304 pixel values adorning each grayscale image, the pursuit of collective synthesis commences in earnest. The mean of all 2304 pixel values from each image is meticulously computed, yielding an array replete with the essence of collective synthesis. These mean pixel values, the epitome of collective resonance, undergo a transformative metamorphosis, transmogrifying into a representative image that embodies the collective essence of the dataset.

Project Management:
The project repository, meticulously curated and nurtured by Anshuman Pattnaik, stands as a testament to the spirit of collaboration and knowledge dissemination. Open to the public, the repository beckons enthusiasts and scholars alike to delve into its depths, fostering an environment of collaborative exploration and intellectual growth. In traversing the corridors of this repository, users are enjoined to honor the ethos of intellectual integrity and attribution, recognizing the contributions of the original architect.

Conclusion:
In the crucible of exploration and innovation, this project stands as a testament to the indomitable spirit of human ingenuity. Through the meticulous orchestration of image processing techniques, dataset creation, and algorithmic synthesis, it embarks on a voyage of discovery, unraveling the mysteries of image generation and data representation. By embracing a philosophy of autonomy and creativity, it inspires future generations of scholars and enthusiasts to chart their own course, forging pathways of discovery and innovation in the boundless realm of image processing.





AP
