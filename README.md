# automatic-question-genrator-from-given-text


## Automatic Question Generator
Automatic Question Generator from Text
An Exam or a Test is key to assessing student performance and plays an important role in gaining confidence. The standard method of producing a questionnaire is hand-made. In this way, some officials draw up a questionnaire. But this approach sometimes does not work because of error-prone, biased, repetition, and scalability. Hence it is important to have a Smart AI-enabled developed model to increase the ability to assess scholars' reading skills. The generated question set of almost any given text helps students to focus on student performance. The proposed system also provides benefits to several educational institutions and NGO-based institutions.

It is an automated system that can take the text input and produce questions to test a student's Perception and Reading ability. In addition, it is ensured that questions are random and duplication free. 

Prerequisites
-------------
```
- Python 3.5+
- NLTK 
- AllenNLP
- FlashText
- Python Keyphrase Extraction (pKE)
- OpenAI GPT-2
```


### Input:
```
There is a lot of volcanic activity at divergent plate boundaries in the oceans. For example, many undersea volcanoes are found 
along the Mid-Atlantic Ridge. This is a divergent plate boundary that runs north-south through the middle of the Atlantic Ocean.
As tectonic plates pull away from each other at a divergent plate boundary, they create deep fissures, or cracks, in the crust.
Molten rock, called magma, erupts through these cracks onto Earth’s surface. At the surface, the molten rock is called lava. 
It cools and hardens, forming rock. Divergent plate boundaries also occur in the continental crust. Volcanoes form at these 
boundaries, but less often than in ocean crust. That’s because continental crust is thicker than oceanic crust. This makes it
more difficult for molten rock to push up through the crust. Many volcanoes form along convergent plate boundaries where one 
tectonic plate is pulled down beneath another at a subduction zone. The leading edge of the plate melts as it is pulled into 
the mantle, forming magma that erupts as volcanoes. When a line of volcanoes forms along a subduction zone, they make up a 
volcanic arc. The edges of the Pacific plate are long subduction zones lined with volcanoes. This is why the Pacific rim 
is called the “Pacific Ring of Fire.
```

### Output:
#### True False questions:<br>
![tf](https://user-images.githubusercontent.com/57886770/176997825-1bce943e-994c-4aa6-a500-dc38ca6bc8be.png)<br>
#### Fill in the Blank questions:<br>
![fill in the blanks](https://user-images.githubusercontent.com/57886770/176997858-a7dff223-790b-4a2d-ab42-595f99440704.png)<br>

### Process Flow Diagram:

![Untitled Workspace (1)](https://user-images.githubusercontent.com/57886770/176993816-221a9d94-769f-4a0b-a4f3-cec0bb26d207.png)
