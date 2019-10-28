
<table></table>


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
<p>Showing only the last 20 entries. You can check all the entries <a href="https://docs.google.com/spreadsheets/d/1ofPAOgQIp7oGORESYlYPGVnYPzaPEJH8zWpCzYF1jWk/edit?usp=sharing" target="_blank">here</a>.
</p><div class="table">
</div>
</div>
<script src="//ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script>
    function importGSS(t) {
        $.each(t.feed.entry.slice(-20), function() {
            $("").addClass("flex-container").append("<tr><td>" + this.gsx$name.$t + "</td><td>" + this.gsx$email.$t + "</td></tr>")
        }), $("").addClass("flex-container").append("<tr><th>Name</th><th>Email</th></tr>")
    }
</script>
<script src="https://spreadsheets.google.com/feeds/list/1ofPAOgQIp7oGORESYlYPGVnYPzaPEJH8zWpCzYF1jWk/1/public/values?alt=json-in-script&amp;callback=importGSS" async=""></script>



mk

 + this.gsx$name.$t + + this.gsx$email.$t + 
 
 
 mk
