---
layout: page
title: About 
---

<html lang="en"><head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1">
<title></title>
<meta name="description" content="">
<link rel="stylesheet" href="webjeda.com/demo/demo.css">
<style>
	  .demo-wrapper {
		  max-width: 80%;
		  margin: 5% auto;
	  }
  </style>
</head>
<body>
<div class="demo-container">
<a class="btn" href="/google-form-customize/">Back to article</a>
<style>
        input {
            padding: 5px 10px;
            margin-bottom: 10px
        }
        .table {
          max-width: 100%;
          overflow: hidden;
        }

        table {
            text-align: left
        }

        td,
        th {
            padding: 10px
        }

        td:first-child,
        th:first-child {
            background-color: #3cb371;
            color: #fff;
            max-width: 170px;
        }

        td:last-child,
        th:last-child {
            background-color: #444;
            color: #fff
        }

        table {
            transform: rotate(180deg)
        }

        table>tr {
            transform: rotate(-180deg)
        }
    </style>
<script>
    var submitted = !1
</script>
<iframe id="hidden_iframe" name="hidden_iframe" onload="submitted&amp;&amp;(window.location=&quot;https://blog.webjeda.com/demo/google-form-customize/&quot;)" style="display:none" __idm_frm__="10737418261"></iframe>
<form action="https://docs.google.com/forms/d/e/1FAIpQLSdqGYth5-G2cP8SILJwjOcJ38vit-Rv8E9SXmtnJUu4ifMcGw/formResponse" method="post" onsubmit="submitted=!0" target="hidden_iframe">
<label>Name</label>
<input maxlength="18" name="entry.742532386" placeholder=" John Doe" required="">
<br>
<label>Email</label>
<input maxlength="18" name="entry.1558941179" placeholder=" john@email.com" required="" type="email">
<br>
<input type="submit" value="Send">
</form>
<p>Showing only the last 20 entries. You can check all the entries <a href="https://docs.google.com/spreadsheets/d/1_vt8il8LpxEi8_DmX0yxxRambpw700cdMC2yMIGWqbk/edit?usp=sharing" target="_blank">here</a>.
</p><div class="table">



</div>
</div>
<script src="//ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script>
    function importGSS(t) {
        $.each(t.feed.entry.slice(-20), function() {
            $("table").addClass("flex-container").append("<tr><td>" + this.gsx$name.$t + "</td><td>" + this.gsx$email.$t + "</td></tr>")
        }), $("table").addClass("flex-container").append("<tr><th>Name</th><th>Email</th></tr>")
    }
</script>
<script src="https://spreadsheets.google.com/feeds/list/1_vt8il8LpxEi8_DmX0yxxRambpw700cdMC2yMIGWqbk/1/public/values?alt=json-in-script&amp;callback=importGSS" async=""></script>


</body></html>
