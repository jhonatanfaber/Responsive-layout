# Responsive layout




```
Basic media queries:

/* Mobile Styles */
  @media (max-width: 400px) {
  }


 /* Tablet Styles */
  @media only screen and (min-width: 401px) and (max-width: 960px) {
   
  } 

   /* Desktop Styles */
   @media only screen and (min-width: 961px) {

  }

flex-wrap: Adding the following property forces items that don’t fit to get bumped down to the next row

.page {
  display: flex;
  flex-wrap: wrap;
}

order: If you want to change the order of your items. The items are placed in the visual order according to that integer, lowest values first. In the following example sign-up div will be shown above content.

.sign-up{
    width: 100%;
    order: 1;
}

.content {
     order: 2;
}

```

