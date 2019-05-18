---
layout: page
title: Submit a talk
short_title: Submit a talk
permalink: /submit-a-talk/
---

<form
    action="https://formspree.io/karlbowden1+1ozpqfwyhwrszswsdmre@boards.trello.com"
    method="POST"
    class="form">

    <input
        type="hidden"
        name="_next"
        value="{{ "/thanks/" | prepend: site.baseurl | prepend: site.url }}"/>

    <input
        type="hidden"
        name="_subject"
        value="Sydney Cocoaheads Talk Submission"/>

    <input
        type="hidden"
        name="_cc"
        value="cch@karlbowden.com"/>

    <input
        type="text"
        name="_gotcha"
        style="display:none"/>

    <input
        type="hidden"
        name="_format"
        value="plain"/>

    <div class="form__group">
        <label
            class="form__label"
            for="Title">Working title of your talk</label>
        <input
            class="form__input-text"
            type="text"
            id="Title"
            name="Title"/>
    </div>

    <div class="form__group">
        <label
            class="form__label"
            for="Description">A rough description</label>
        <textarea
            class="form__input-textarea"
            id="Description"
            name="Description"
            rows="3"></textarea>
    </div>

    <div class="form__group">
        <label
            class="form__label"
            for="Format-full">Talk format</label>
        <div class="form__radio-item">
            <label class="form__radio-label">
                <input
                    class="form__input-radio"
                    id="Format-full"
                    type="radio"
                    name="Format"
                    value="Full presentation"/>
                Full presentation (20-30 minutes)
            </label>
        </div>
        <div class="form__radio-item">
            <label class="form__radio-label">
                <input
                    class="form__input-radio"
                    id="Format-lightning"
                    type="radio"
                    name="Format"
                    value="Lightning talk">
                Lightning talk (5-10 minutes)
            </label>
        </div>
    </div>

    <div class="form__group">
        <label
            class="form__label"
            for="Event">Which event?</label>
        <select
            class="form__input-select"
            id="Event"
            name="Event">
            <option value="">Select an upcoming event</option>
            <option value="June 2019">Sydney Cocoaheads - June 20th 2019</option>
            <option value="July 2019">Sydney Cocoaheads - July 18th 2019</option>
            <option value="August 2019">Sydney Cocoaheads - August 15th 2019</option>
            <option value="September 2019">Sydney Cocoaheads - September 19th 2019</option>
            <option value="October 2019">Sydney Cocoaheads - October 17th 2019</option>
            <option value="November 2019">Sydney Cocoaheads - November 21th 2019</option>
            <option value="December 2019">Sydney Cocoaheads - December 19th 2019</option>
            <option value="January 2020">Sydney Cocoaheads - January 16th 2020</option>
            <option value="February 2020">Sydney Cocoaheads - February 20st 2020</option>
            <option value="March 2020">Sydney Cocoaheads - March 19st 2020</option>
            <option value="April 2020">Sydney Cocoaheads - April 16th 2020</option>
            <option value="May 2020">Sydney Cocoaheads - May 21th 2020</option>
        </select>
    </div>

    <div class="form__group">
        <label
            class="form__label"
            for="Name">Your name</label>
        <input
            class="form__input-text"
            id="Name"
            type="text"
            name="Name">
    </div>

    <div class="form__group">
        <label
            class="form__label"
            for="email">Email</label>
        <input
            class="form__input-text form__input-text--email"
            id="email"
            type="email"
            name="email">
        <span
            class="form__help-message">
            Email address won't be be published, it's just so we can get in touch.
        </span>
    </div>

    <div class="form__group">
        <label
            class="form__label"
            for="Twitter">Twitter (optional)</label>
        <input
            class="form__input-text"
            id="Twitter"
            type="text"
            name="Twitter"
            placeholder="@cocoaheadsau">
    </div>

    <div class="form__group">
        <label
            class="form__label"
            for="Comments">Additional comments, notes or instructions</label>
        <textarea
            class="form__input-textarea"
            rows="3"
            id="Comments"
            name="Comments"></textarea>
    </div>

    <button
        class="form__button form__button--submit"
        type="submit">Submit</button>

</form>
