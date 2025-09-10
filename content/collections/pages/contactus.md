---
id: 58ed3787-6b3a-47de-b929-bfd7e8d20367
blueprint: page
title: Contact
author: c92c5cd1-119e-4e14-b417-6374346d994d
template: default
updated_by: c92c5cd1-119e-4e14-b417-6374346d994d
updated_at: 1757532485
code:
  code: |-
    <section class="text-white py-2" style="
    background-color: #ff3700d1;>
        <div class="container">
            <div class="row">
                <div class="col-12 text-center">
                    <h1 class="display-2 fw-bold mb-3 animate__animated animate__fadeInDown">Contact Us</h1>
                    <p class="lead mb-0 animate__animated animate__fadeInUp">We're here to help and answer any questions you might have</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="py-5">
        <div class="container">
            <div class="row g-5">
                <!-- Contact Form -->
                <div class="col-lg-8">
                    <div class="card shadow-lg border-0 animate__animated animate__fadeInLeft">
                        <div class="card-body p-5">
                            <h3 class="card-title fw-bold text-success mb-4">
                                <i class="fas fa-paper-plane me-2"></i>Send us a Message
                            </h3>
                            <form id="contactForm">
                                <div class="row g-2">
                                    <div class="col-md-6">
                                        <label for="firstName" class="form-label">First Name *</label>
                                        <input type="text" class="form-control " id="firstName" required>
                                    </div>
                                    <div class="col-md-6">
                                        <label for="lastName" class="form-label">Last Name *</label>
                                        <input type="text" class="form-control" id="lastName" required>
                                    </div>
                                </div>

                                <div class="row g-3 mt-3">
                                    <div class="col-md-6">
                                        <label for="email" class="form-label">Email Address *</label>
                                        <input type="email" class="form-control" id="email" required>
                                    </div>
                                    <div class="col-md-6">
                                        <label for="phone" class="form-label">Phone Number</label>
                                        <input type="tel" class="form-control" id="phone">
                                    </div>
                                </div>

                                <div class="mt-3">
                                    <label for="subject" class="form-label">Subject *</label>
                                    <select class="form-select" id="subject" required>
                                        <option value="">Choose a subject...</option>
                                        <option value="membership">Membership Inquiry</option>
                                        <option value="loans">Loan Services</option>
                                        <option value="savings">Savings Account</option>
                                        <option value="remittance">Remittance Services</option>
                                        <option value="insurance">Insurance Services</option>
                                        <option value="complaint">Complaint</option>
                                        <option value="feedback">Feedback</option>
                                        <option value="other">Other</option>
                                    </select>
                                </div>

                                <div class="mt-3">
                                    <label for="message" class="form-label">Message *</label>
                                    <textarea class="form-control" id="message" rows="3"
                                              placeholder="Please describe your inquiry or message..." required></textarea>
                                </div>

                                <div class="mt-4">
                                    <button type="submit" class="btn btn-success btn-sm px-2 py-2">
                                        <i class="fas fa-paper-plane me-2"></i>Send Message
                                    </button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>

                <!-- Contact Information -->
                <div class="col-lg-4">
                    <div class="row g-4">
                        <!-- Office Information -->
                        <div class="col-12">
                            <div class="card border-0 shadow-sm h-100 animate__animated animate__fadeInRight">
                                <div class="card-body p-4">
                                    <h4 class="card-title fw-bold text-success mb-4">
                                        <i class="fas fa-building me-2"></i>Head Office
                                    </h4>
                                    <div class="mb-3">
                                        <div class="d-flex align-items-start mb-2">
                                            <i class="fas fa-map-marker-alt text-success me-3 mt-1"></i>
                                            <div>
                                                <strong>Address:</strong><br>
                                                Thakurbaba-1, Bardiya, Nepal
                                            </div>
                                        </div>
                                        <div class="d-flex align-items-center mb-2">
                                            <i class="fas fa-phone-alt text-success me-3"></i>
                                            <div>
                                                <strong>Phone:</strong><br>
                                                <a href="tel:084-XXXXXX" class="text-decoration-none">084-XXXXXX</a>
                                            </div>
                                        </div>
                                        <div class="d-flex align-items-center mb-2">
                                            <i class="far fa-envelope text-success me-3"></i>
                                            <div>
                                                <strong>Email:</strong><br>
                                                <a href="mailto:wanosaccos@gmail.com" class="text-decoration-none">wanosaccos@gmail.com</a>
                                            </div>
                                        </div>
                                        <div class="d-flex align-items-center">
                                            <i class="fas fa-clock text-success me-3"></i>
                                            <div>
                                                <strong>Business Hours:</strong><br>
                                                Sun - Fri: 10:00 AM - 5:00 PM<br>
                                                Saturday: Closed
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Information Officer -->
                        <div class="col-12">
                            <div class="card border-0 shadow-sm h-100 animate__animated animate__fadeInRight" style="animation-delay: 0.2s;">
                                <div class="card-body p-4 text-center">
                                    <h4 class="card-title fw-bold text-success mb-2">
                                        <i class="fas fa-user-tie me-2"></i>Information Officer
                                    </h4>

                                    <h5 class="text-success fw-bold">Vijaya Khanal</h5>
                                    <p class="text-muted mb-3">Information Officer</p>
                                    <div class="d-flex flex-column gap-2">
                                        <a href="tel:9868292191" class="btn btn-outline-success btn-sm">
                                            <i class="fas fa-phone me-2"></i>9868292191
                                        </a>
                                        <a href="mailto:vijaykhanal0@gmail.com" class="btn btn-outline-success btn-sm">
                                            <i class="far fa-envelope me-2"></i>Email
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>


                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Map Section -->
    <section class="py-5 bg-white">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="card shadow-lg border-0">
                        <div class="card-header bg-success text-white py-3">
                            <h4 class="mb-0 ">
                                <i class="fas fa-map-marked-alt me-2"></i>Find Us on Map
                            </h4>
                        </div>
                        <div class="card-body p-0">
                            <div class="ratio ratio-21x9">
                                <iframe
                                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3532.741234567890!2d81.234567!3d28.234567!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39a1234567890123%3A0x1234567890abcdef!2sThakurbaba-1%2C%20Bardiya%2C%20Nepal!5e0!3m2!1sen!2snp!4v1234567890123!5m2!1sen!2snp"
                                    style="border:0;"
                                    allowfullscreen=""
                                    loading="lazy"
                                    referrerpolicy="no-referrer-when-downgrade">
                                </iframe>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
  mode: htmlmixed
content_blocks:
  -
    type: set
    attrs:
      id: mf5loza5
      values:
        type: html_block
        html:
          code: |-
            <section class="text-white py-2" style="
            background-color: #ff3700d1;>
                <div class="container">
                    <div class="row">
                        <div class="col-12 text-center">
                            <h1 class="display-2 fw-bold mb-3 animate__animated animate__fadeInDown">Contact Us</h1>
                            <p class="lead mb-0 animate__animated animate__fadeInUp">We're here to help and answer any questions you might have</p>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Contact Section -->
            <section class="py-5">
                <div class="container">
                    <div class="row g-5">
                        <!-- Contact Form -->
                        <div class="col-lg-8">
                            <div class="card shadow-lg border-0 animate__animated animate__fadeInLeft">
                                <div class="card-body p-5">
                                    <h3 class="card-title fw-bold text-success mb-4">
                                        <i class="fas fa-paper-plane me-2"></i>Send us a Message
                                    </h3>
                                    <form id="contactForm">
                                        <div class="row g-2">
                                            <div class="col-md-6">
                                                <label for="firstName" class="form-label">First Name *</label>
                                                <input type="text" class="form-control " id="firstName" required>
                                            </div>
                                            <div class="col-md-6">
                                                <label for="lastName" class="form-label">Last Name *</label>
                                                <input type="text" class="form-control" id="lastName" required>
                                            </div>
                                        </div>

                                        <div class="row g-3 mt-3">
                                            <div class="col-md-6">
                                                <label for="email" class="form-label">Email Address *</label>
                                                <input type="email" class="form-control" id="email" required>
                                            </div>
                                            <div class="col-md-6">
                                                <label for="phone" class="form-label">Phone Number</label>
                                                <input type="tel" class="form-control" id="phone">
                                            </div>
                                        </div>

                                        <div class="mt-3">
                                            <label for="subject" class="form-label">Subject *</label>
                                            <select class="form-select" id="subject" required>
                                                <option value="">Choose a subject...</option>
                                                <option value="membership">Membership Inquiry</option>
                                                <option value="loans">Loan Services</option>
                                                <option value="savings">Savings Account</option>
                                                <option value="remittance">Remittance Services</option>
                                                <option value="insurance">Insurance Services</option>
                                                <option value="complaint">Complaint</option>
                                                <option value="feedback">Feedback</option>
                                                <option value="other">Other</option>
                                            </select>
                                        </div>

                                        <div class="mt-3">
                                            <label for="message" class="form-label">Message *</label>
                                            <textarea class="form-control" id="message" rows="3"
                                                      placeholder="Please describe your inquiry or message..." required></textarea>
                                        </div>

                                        <div class="mt-4">
                                            <button type="submit" class="btn btn-success btn-sm px-2 py-2">
                                                <i class="fas fa-paper-plane me-2"></i>Send Message
                                            </button>
                                        </div>
                                    </form>
                                </div>
                            </div>
                        </div>

                        <!-- Contact Information -->
                        <div class="col-lg-4">
                            <div class="row g-4">
                                <!-- Office Information -->
                                <div class="col-12">
                                    <div class="card border-0 shadow-sm h-100 animate__animated animate__fadeInRight">
                                        <div class="card-body p-4">
                                            <h4 class="card-title fw-bold text-success mb-4">
                                                <i class="fas fa-building me-2"></i>Head Office
                                            </h4>
                                            <div class="mb-3">
                                                <div class="d-flex align-items-start mb-2">
                                                    <i class="fas fa-map-marker-alt text-success me-3 mt-1"></i>
                                                    <div>
                                                        <strong>Address:</strong><br>
                                                        Thakurbaba-1, Bardiya, Nepal
                                                    </div>
                                                </div>
                                                <div class="d-flex align-items-center mb-2">
                                                    <i class="fas fa-phone-alt text-success me-3"></i>
                                                    <div>
                                                        <strong>Phone:</strong><br>
                                                        <a href="tel:9858026766" class="text-decoration-none">084-XXXXXX</a>
                                                    </div>
                                                </div>
                                                <div class="d-flex align-items-center mb-2">
                                                    <i class="far fa-envelope text-success me-3"></i>
                                                    <div>
                                                        <strong>Email:</strong><br>
                                                        <a href="mailto:wanosaccos@gmail.com" class="text-decoration-none">wanosaccos@gmail.com</a>
                                                    </div>
                                                </div>
                                                <div class="d-flex align-items-center">
                                                    <i class="fas fa-clock text-success me-3"></i>
                                                    <div>
                                                        <strong>Business Hours:</strong><br>
                                                        Sun - Fri: 10:00 AM - 5:00 PM<br>
                                                        Saturday: Closed
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>

                                <!-- Information Officer -->
                                <div class="col-12">
                                    <div class="card border-0 shadow-sm h-100 animate__animated animate__fadeInRight" style="animation-delay: 0.2s;">
                                        <div class="card-body p-4 text-center">
                                            <h4 class="card-title fw-bold text-success mb-2">
                                                <i class="fas fa-user-tie me-2"></i>Information Officer
                                            </h4>

                                            <h5 class="text-success fw-bold">Vijaya Khanal</h5>
                                            <p class="text-muted mb-3">Information Officer</p>
                                            <div class="d-flex flex-column gap-2">
                                                <a href="tel:9868292191" class="btn btn-outline-success btn-sm">
                                                    <i class="fas fa-phone me-2"></i>9868292191
                                                </a>
                                                <a href="mailto:vijaykhanal0@gmail.com" class="btn btn-outline-success btn-sm">
                                                    <i class="far fa-envelope me-2"></i>Email
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                </div>


                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Map Section -->
            <section class="py-5 bg-white">
                <div class="container">
                    <div class="row">
                        <div class="col-12">
                            <div class="card shadow-lg border-0">
                                <div class="card-header bg-success text-white py-3">
                                    <h4 class="mb-0 ">
                                        <i class="fas fa-map-marked-alt me-2"></i>Find Us on Map
                                    </h4>
                                </div>
                                <div class="card-body p-0">
                                    <div class="ratio ratio-21x9">
                                        <iframe
                                            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3532.741234567890!2d81.234567!3d28.234567!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39a1234567890123%3A0x1234567890abcdef!2sThakurbaba-1%2C%20Bardiya%2C%20Nepal!5e0!3m2!1sen!2snp!4v1234567890123!5m2!1sen!2snp"
                                            style="border:0;"
                                            allowfullscreen=""
                                            loading="lazy"
                                            referrerpolicy="no-referrer-when-downgrade">
                                        </iframe>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
          mode: htmlmixed
  -
    type: paragraph
---
hi