---
layout: single
title: Sign-up
thumbnail: assets/img/form.png
description: >-
    Fill this form to sign up for the meetings and we'll contact you as soon as possible.
permalink: /sign-up
---

<form class="row mb-3 needs-validation justify-content-center" id="form" action="https://docs.google.com/forms/u/0/d/e/1FAIpQLSdUkg_eS9MNEuwxdH-geFnUIv5r4h_v4LrgP-IugNj4__v9Mg/formResponse" novalidate>
    <div class="col-12 col-md-6 p-1">
        <div class="form-floating">
            <input type="text" class="form-control" id="firs-name" placeholder="Mohammad" pattern="^[a-zA-Z]+(([',. -][a-zA-Z ])?[a-zA-Z]*)*$" required name="entry.691620484">
            <label for="firs-name">First name</label>
            <div class="invalid-feedback">
                Enter your first name correctly.
            </div>
        </div>
    </div>
    <div class="col-12 col-md-6 p-1">                   
        <div class="form-floating">
            <input type="text" class="form-control" id="last-name" placeholder="Mohammadi" pattern="^[a-zA-Z]+(([',. -][a-zA-Z ])?[a-zA-Z]*)*$" required name="entry.771608105">
            <label for="last-name">Last name</label>
            <div class="invalid-feedback">
                Enter your last name correctly.
            </div>
        </div>
    </div>              
    <div class="col-12 col-md-6 p-1">                    
        <div class="form-floating">
            <input type="text" class="form-control" id="email" placeholder="name@example.com" pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,4}$" required name="entry.819637256">
            <label for="email">Email address (e.g., example@gmail.com)</label>
            <div class="invalid-feedback">
                Enter your email correctly.
            </div>
        </div>
    </div>                
    <div class="col-12 col-md-6 p-1">                   
        <div class="form-floating">
            <input type="text" class="form-control" id="phone-number" placeholder="+989131112233" pattern="09\d{9}" required name="entry.1984722826">
            <label for="phone-number">Phone number (e.g., 09131112233)</label>
            <div class="invalid-feedback">
                Enter your phone number correctly.
            </div>
        </div>
    </div>               
    <div class="col-12 p-1">
        <div class="form-floating">
            <textarea type="textarea" class="form-control" id="background" placeholder="name@example.com" rows="3" required name="entry.259299195"></textarea>
            <label for="background">Background</label>
            <div class="invalid-feedback">
                This cannot be empty.
            </div>
        </div>
    </div>              
    <div class="col-12 p-1">       
        <div class="form-floating">
            <textarea type="textarea" class="form-control" id="interests" placeholder="name@example.com" rows="3" required name="entry.898511114"></textarea>
            <label for="interests">Interests</label>
            <div class="invalid-feedback">
                This cannot be empty.
            </div>
        </div>
    </div>
    <div class="col-12 p-1">       
        <div class="col text-center">
            <input type="submit" class="btn btn-secondary" value="Sign-up">
        </div>
    </div>
</form>
<div id="success" class="alert alert-success" style="display: none;" role="alert">
    &#127801;
    You have successfully signed up for Isfahan Neuroscience Meetings. We will contact you as soon as possible.           
</div>