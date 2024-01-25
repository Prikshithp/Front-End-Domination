#CSS
- ##boiler plate for CSS
- *{
  -  margin: 0%;
   - padding: 0%;
   - box-sizing: border-box;
 - }
- body,html{
  -  width: 100%;
   - height: 100%;
- }
- #Color -> text color
- #bgc -> bakground,s color

- Units in CSS
- px -> not prefered , every screen has different pixels in screen
- %-> screen ke respect me kudko badalta hai || parent se value leta hai
- vw and vh -> screen se value leta hai
- em -> changes respect to font size // agar font size is 16px so 2em is 32 // stays fixed so change ke liye font size change kro
- rem > html font size root element (html eleemnt)

- max width  max height -> create a hook or range . agar kaam hua tho change ni hoga
- max height min width -> vice versa

- Fonts -> 2 types sans serif or serif
-  font-weight: 200;
-  text-transform: uppercase;
-  text-decoration: line-through;
-  font-size: 2vw;
-    line-height:0.9;
-       text- lign: justify;  /* left right center */

-  Box-Model
-  padding -> box ke andar
-  margin-> box ke bahar
-  border Margin or pagging ke piche me

- Display Property
- Block -> saare place leta , ek element ek jagah m hi aaega eg -> p 
- inline -> adjust ho jatte par height width change ni kar skte ->> here comes the inline-block element eg -> a

- Positions
- Absolute -> uppar uthaege
- relative -> relation to box . parent relative and child absolute
