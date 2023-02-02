# assignment2-Mannam

# Mannam Sandeep

###### My favorite sport is Cricket

I love playing crciket since childhood. I love **batting** and **bowling**.

---

# RCB
1. virat
2. Anuj
3. Dinesh

* SRH
* KKR
* CSK <br>
[redirecting to nextpage](AboutMe.md)

---
# Fav Countries

I am gonna visit my fav countries which are in the below table

| **Country_Name** | **Reason** | **Days**|
| --- | :---: | ---: |
|Brazil|  Is famous for stunning beaches| 15 |
|Germany| famous for cultural beauty and beer| 15 |
|Finland| happiest country in the world| 15 |
|Canada| It's a place of land where people leave independently| 15 |

---

## Funny quotes

> Even in hard times there's a possibility to have fun. - *james*

> Live for today and let tomorrow come later. - *priya*

---

## JQuery Stack Overflow
> [jQuery Tips and Tricks](https://stackoverflow.com/questions/7717527/smooth-scrolling-when-clicking-an-anchor-link)

```

// Select all links with hashes
$('a[href*="#"]')
  // Remove links that don't actually link to anything
  .not('[href="#"]')
  .not('[href="#0"]')
  .click(function(event) {
    // On-page links
    if (
      location.pathname.replace(/^\//, '') == this.pathname.replace(/^\//, '') 
      && 
      location.hostname == this.hostname
    ) {
      // Figure out element to scroll to
      var target = $(this.hash);
      target = target.length ? target : $('[name=' + this.hash.slice(1) + ']');
      // Does a scroll target exist?
      if (target.length) {
        // Only prevent default if animation is actually gonna happen
        event.preventDefault();
        $('html, body').animate({
          scrollTop: target.offset().top
        }, 1000, function() {
          // Callback after animation
          // Must change focus!
          var $target = $(target);
          $target.focus();
          if ($target.is(":focus")) { // Checking if the target was focused
            return false;
          } else {
            $target.attr('tabindex','-1'); // Adding tabindex for elements not focusable
            $target.focus(); // Set focus again
          };
        });
      }
    }
  });


```


> [Snippet code link](https://css-tricks.com/snippets/jquery/smooth-scrolling/)










