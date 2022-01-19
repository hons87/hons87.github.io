---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: "welcome to basser.cs.su.oz.au"
---
## basser.cs.su.oz.au

```txt
login: root
password:
Welcome to the Eighth Edition Research Unix
Running on a DEC VAX 11/780 with 8MB memory

                        88              
                        ""              
                                        
88       88 8b,dPPYba,  88 8b,     ,d8  
88       88 88P'   `"8a 88  `Y8, ,8P'   
88       88 88       88 88    )888(     
"8a,   ,a88 88       88 88  ,d8" "8b,   
 `"YbbdP'Y8 88       88 88 8P'     `Y8 

 #
```

## A photo of us in 1987

Outside the Madsen building at University of Sydney.

<div class="photoswipe-gallery">
  {% include photo.html
      url="/assets/images/1987.jpeg"
      thumb_width="1280" thumb_height="807"
      full_width="2560" full_height="1613"
      caption="1987" alt="1987"
  %}
</div>

## Photos of us in 2022

Taken by Stuart Pook.

<div class="photoswipe-gallery">
  {% include photo.html
      url="/assets/images/Standing.jpeg"
      thumb_width="640" thumb_height="459"
      full_width="2560" full_height="1836"
      caption="Standing outside Madsen building" alt="Standing outside Madsen building"
  %}
  {% include photo.html
      url="/assets/images/Sitting.jpeg"
      thumb_width="640" thumb_height="381"
      full_width="2560" full_height="1523"
      caption="Sitting outside Madsen building" alt="Sitting outside Madsen building"
  %}
</div>

{% include photoswipe.html %}
