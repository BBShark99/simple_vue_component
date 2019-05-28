<template>
  <div class="contact">
    <h1>Welcome to Vue.js App</h1>
    <div class="card">
        <h3>Contact & Feedback</h3>
        <ul>
            <li>Feedback – Please tell us what you think, we'll get back to you in a day or two.</li>
            <li>Contact info – Email and post.</li>
            <li>Support our work – Want to help?</li>
        </ul>
    </div>
    <div class="card">
        <h3>https://vuejs.org</h3>
        <ul>
            <li>Time and Date AS – Who are we?</li>
            <li>Time and Date AS is a fast growing company based in Stavanger, Norway. We are always looking for good candidates to join our team.</li>
            <li>Want to work for us?</li>
        </ul>
    </div>
    <div class="card">
        <h3>Advertising</h3>
        <p>Millions of users see your ads on:</p>
        <ul>
            <li>timeanddate.com in English.</li>
            <li>timeanddate.de in German.</li>
            <li>timeanddate.no in Norwegian.</li>
        </ul>
        <p>We value your privacy!</p>
    </div>
  </div>
</template>

<style>
.contact h1{
  font-size: 20px;
  text-shadow: 3px 3px 1px rgb(197, 194, 194);
}
.contact .card{
    border: 1px solid gray;
    border-radius: 8px;
    padding: 10px;
    margin:5px;
    font-size:15px;
    font-family: Helvetica, Arial, Sans-Serif;
    color: #454545;
    display: inline-grid;
    width:30%;
    min-height:270px;

}
.card h1{
    font-size: 30px;
}
.card h3{
    font-size: 24px;
    letter-spacing: 2px;
    padding-bottom: none;
}
.card li{
    text-align: left;
    padding-bottom:5px;
}


</style>
