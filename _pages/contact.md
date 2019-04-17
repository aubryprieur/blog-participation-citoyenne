---
title: "Contact"
permalink: "/contact.html"
---

<form action="https://getsimpleform.com/messages?form_api_token=42c08439ae27e8f0cfdfd3a37509cc1e" method="POST">
  <input type="hidden" name="redirect_to" value="https://www.participationcitoyenne.org/merci.html">
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
  <input class="btn btn-success" type="submit" value="Envoyer">
</form>
