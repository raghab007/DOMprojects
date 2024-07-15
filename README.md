# Simple javaScript DOM projects

#Code solutions

## Project1 code (Background Changer)
'''
const allBtns = document.querySelectorAll('.button');
for (let btn of allBtns) {
  btn.addEventListener('click', function (e) {
    //document.body.style.backgroundColor = this.//getAttribute('id');
    document.body.style.backgroundColor = e.target.id;
  });
}
'''



