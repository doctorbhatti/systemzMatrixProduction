<template>
    <div class="contact-area area-padding">
        <div class="container">
            <div class="row">
                <div class="contact-inner">
                    <div class="col-md-4 col-sm-4 col-xs-12">
                        <div class="contact-icon text-center">
                            <div class="single-icon">
                                <i class="ti-mobile"></i>
                                <p>
                                    Call : <a href="tel:+923099992219"></a>(+92) 330-7672275<br />
                                    <span>Monday-Friday (10 AM - 6 PM)</span>
                                </p>
                            </div>
                        </div>
                    </div>

                    <div class="col-md-4 col-sm-4 col-xs-12">
                        <div class="contact-icon text-center">
                            <div class="single-icon">
                                <i class="ti-email"></i>
                                <p>
                                    Email : <a href="mailto: info@systemzmatrix.com"></a>info@systemzmatrix.com<br />
                                    <span>Web: <a href="https://systemzmatrix.com"></a>www.systemzmatrix.com</span>
                                </p>
                            </div>
                        </div>
                    </div>

                    <div class="col-md-4 col-sm-4 col-xs-12">
                        <div class="contact-icon text-center">
                            <div class="single-icon">
                                <i class="ti-location-pin"></i>
                                <p>
                                    Location : 4th floor, 1109 F,<br />
                                    <span>Commercial Area, State Life Co operative housing Society Lahore</span>
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-md-6 col-sm-6 col-xs-12">
                    <div class="map-area">
                        <iframe
                            width="550"
                            height="334"
                            src="https://www.google.com/maps/embed/v1/place?q=31.445298,+74.396657&key=AIzaSyBFw0Qbyq9zTFTd-tUY6dZWTgaQzuU17R8"
                            className="google-map__contact"
                            allowFullScreen
                        >
                        </iframe>
                    </div>
                </div>

                <div class="col-md-6 col-sm-6 col-xs-12">
                    <div class="contact-form">
                        <div class="row">
                            <form
                                id="contactForm"
                                method="POST"
                                action="#"
                                class="contact-form"
                            >
                                <div class="col-md-6 col-sm-6 col-xs-12">
                                    <input
                                        type="text"
                                        id="name"
                                        class="form-control"
                                        placeholder="Name"
                                        required
                                        data-error="Please enter your name"
                                    />
                                    <div class="help-block with-errors"></div>
                                </div>
                                <div class="col-md-6 col-sm-6 col-xs-12">
                                    <input
                                        type="email"
                                        class="email form-control"
                                        id="email"
                                        placeholder="Email"
                                        required
                                        data-error="Please enter your email"
                                    />
                                    <div class="help-block with-errors"></div>
                                </div>
                                <div class="col-md-12 col-sm-12 col-xs-12">
                                    <input
                                        type="text"
                                        id="msg_subject"
                                        class="form-control"
                                        placeholder="Subject"
                                        required
                                        data-error="Please enter your message subject"
                                    />
                                    <div class="help-block with-errors"></div>
                                </div>
                                <div class="col-md-12 col-sm-12 col-xs-12">
                                    <textarea
                                        id="message"
                                        rows="7"
                                        placeholder="Massage"
                                        class="form-control"
                                        required
                                        data-error="Write your message"
                                    ></textarea>
                                    <div class="help-block with-errors"></div>
                                </div>
                                <div
                                    class="col-md-12 col-sm-12 col-xs-12 text-center"
                                >
                                    <button
                                        type="submit"
                                        id="submit"
                                        class="add-btn contact-btn"
                                    >
                                        Send Message
                                    </button>
                                    <div
                                        id="msgSubmit"
                                        class="h3 text-center hidden"
                                    ></div>
                                    <div class="clearfix"></div>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "ContactDetails",
};
</script>

<style scoped>
</style>
