<template>
  <section class="contact" id="contact">
        <div class="container">
            <h2 class="has-ellipsis-left text-center wow fadeInUp">Contact Me</h2>
            <!-- <p class="lead text-center wow fadeInUp" data-wow-delay="0.3s">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p> -->

            <div class="form-holder">
                <form action="https://formspree.io/minhltuit@gmail.com" id="contact-form" method="POST">
                    <div class="row">
                        <div class="col-md-6 form-group">
                            <input type="text" name="username" id="username" class="form-control" required>
                            <label for="username">Enter your name</label>
                        </div>
                        <div class="col-md-6 form-group">
                            <input type="email" name="useremail" class="form-control" id="email" required>
                            <label for="email">Enter your email address</label>
                        </div>
                        <div class="col-md-12 form-group">
                            <input type="text" name="subject" class="form-control" id="subject" required>
                            <label for="subject">Subject</label>
                        </div>
                        <div class="col-md-12 form-group">
                            <textarea name="message" id="message" class="form-control" required></textarea>
                            <label for="message">How can I help you?</label>
                        </div>

                        <div class="col-md-12 form-group text-center no-margin-bottom ">
                            <input type="submit" class="btn btn-template" value="Send Your Message">
                        </div>
                    </div>
                </form>
            </div>

            <ul class="contact-details list-unstyled d-flex justify-content-center flex-column flex-md-row">
                <li>
                    <div class="icon">
                        <i class="fa fa-envelope-o"></i>
                    </div>
                    <p><a href="mailto:minhltuit@gmail.com">minhltuit@gmail.com</a></p>
                </li>
                <li>
                    <div class="icon">
                        <i class="fa fa-map-marker"></i>
                    </div>
                    <p>571/29 Pham Van Bach, Tan Binh Dict, Ho Chi Minh City</p>
                </li>
                <li>
                    <div class="icon">
                        <i class="fa fa-phone"></i>
                    </div>
                    <p><a href="tel:01685355808">(+84) 1685 355 808</a></p>
                </li>
            </ul>
        </div>
    </section>
</template>

<script>
export default {
  name: 'Contact'
}
</script>