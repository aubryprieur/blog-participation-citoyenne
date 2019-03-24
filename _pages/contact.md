---
title: "Contact"
permalink: "/contact.html"
---

<form action="https://formspree.io/{{site.email}}" method="POST">
<p class="mb-4">Merci d'envoyer un message aux membres du site "{{site.name}}". Nous vous répondrons le plus rapidement possible!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Votre nom*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="Adresse E-mail*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Votre message*" required></textarea>
<input class="btn btn-success" type="submit" value="Send">
</form>
