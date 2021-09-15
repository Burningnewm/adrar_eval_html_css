# Adrar Eval HTML/CSS

This is the first `HTML/CSS` eval I've had while training at Adrar Montpellier: 

* We had to use only flex and grid to build Website.

* Responsive was made and website tested in several browsers.

* Commentaries are in french as per trainer's request.

### Trainer's feedbacks:
* Integration was done in time, model was correctly followed and `HTML` is close to perfection ^^
* `HTML`:
  * `Head`: Good! -> there's even a favicon which was not requested but appreciated.
  * `Body`: Honestly `HTML` is clean, good construction, everything is respected, class names are coherents ... Only little bug on special characters encoding. 
    * /!\ `Body > Footer`: You can't create a form without `form` element. Nothing can be done with `input` element itself. `input` element can't send data without a `form` element /!\
    *   Should have used `a` instead of `input` index.html line 41: 
  ```html 
  <input type="button" value="DÉCOUVREZ NOUS"> 
  ```
* `CSS`:
  *   Flex is correctly managed
  *   There needs to be a box shadow on `header`, `footer`, `h2`, `p`
  *   Fontawesome is a little small
  *   Font did not render correctly on all sections
  *   /!\ Header's Logo is kind of out of shape (`grrrrr` as per trainer's feedback ^^)/!\

### Things to improve upon:

>`HTML`:
>> need to review some elements to make sure they behave as expected (e.g. `input` within `form` element)


>`CSS`:
>> Need to review font behavior -> probably not placed at the right place in style sheet
>>> Need to correctly use external images for them to be correctly shaped
>>>> Personal note: `CSS` sheet could be smaller -> need to double check for some elements to be grouped together. / Next step for responsive is Mobile first!!!   


     
