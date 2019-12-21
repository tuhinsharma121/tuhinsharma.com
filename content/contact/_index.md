+++
# Homepage
type = "widget_page"
headless = true  # Homepage is headless, other widget pages are not.
+++

<div class="mb-3">
   <form 
      action="https://formspree.io/mgeerwdy"
      method="POST">
      <div class="form-group form-inline">
         <label class="sr-only" for="inputName">{{ Subject "subject" }}</label>
         <input type="text" name="name" class="form-control w-100" id="inputName" placeholder="Subject" required>
      </div>
      <div class="form-group">
         <label class="sr-only" for="inputMessage">Message "contact_message" }}</label>
         <textarea name="message" class="form-control" id="inputMessage" rows="5" placeholder="Message" required></textarea>
      </div>
      <div class="form-group form-inline">
         <label class="sr-only" for="inputName">{{ Name "contact_name" }}</label>
         <input type="text" name="name" class="form-control w-100" id="inputName" placeholder="Name" required>
      </div>
      <div class="form-group form-inline">
         <label class="sr-only" for="inputEmail">Email "contact_email" }}</label>
         <input type="email" name="email" class="form-control w-100" id="inputEmail" placeholder="Email" required>
      </div>
      <button type="submit" class="btn btn-outline-primary px-3 py-2">Send</button>
   </form>
</div>
    
 
    

