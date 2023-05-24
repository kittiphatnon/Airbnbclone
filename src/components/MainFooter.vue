<template>
    <div class="footer border">
        <div class="footer-left">
            <p>© 2023 Airbnb, Inc.</p>
            <p>Privacy</p>
            <p>Terms</p>
            <p>Sitemap</p>
        </div>
        <div class="footer-right">
            <p>English</p>
            <p>USD</p>
            <p>$</p>
        </div> 
    </div>
  </template>
  
  <style scoped>
  .footer {
    height: 30px;
    background-color: #f5f5f5;
    border-top: 1px solid lightgrey;
    bottom: 0;
    position: sticky;
    border-top: 15px;
    border-bottom: 15px;
  }
  
  .footer-left {
    display:flex;
    white-space: nowrap;
    float:left;
  }
  .footer-right {
    display:flex;
    white-space: nowrap;
    float:right;
  }
  
  .footer p {
    margin-left: 20px;
    margin-right: 20px;
    color: grey;
  }
  
  /* .footer-left {
      margin-left: 20px;
      margin-right: 20px;
      color: grey;
      float: left;
  } */
  
  </style>
  