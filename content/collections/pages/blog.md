---
id: 52f43ab7-0f9b-4fd5-8766-5b790d2d6d2c
blueprint: page
title: Blog
author: cbc10183-d3d3-44b1-bec1-15f2c88b92d3
template: home
seo_title: iPersonal
meta_keywords: 'keywords, keys, tags'
meta_description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis laboriosam repudiandae'
og_title: iPersonal
og_description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis laboriosam repudiandae'
twitter_card_type: summary
twitter_site: '@yoursite'
updated_by: cbc10183-d3d3-44b1-bec1-15f2c88b92d3
updated_at: 1725889926
parent: home
og_image: images/designer-(3).jpeg
og_site_name: 'Revolve 314 Digital'
content:
  -
    type: set
    attrs:
      id: m0uucfae
      values:
        type: home_hero
        logo_text: i.Personal
        logo_title: i.Personal
        title_1: '👋 Our Blog'
        title_2: 'Latest News and Blog'
        heading: 'Latest News and Blog'
        description: "Expert Statamic Web Developer & CMS Specialist crafting fast, secure, and scalable websites. Proficient in building custom themes, templates, and addons. Passionate about creating engaging digital experiences with Statamic's flexible and user-friendly CMS. Let's bring your online vision to life with tailored Statamic solutions."
        edit_template: false
        custom_template: |-
          <!-- Header Start -->
                  <div class="container-fluid" id="ipersonalHome">
                      <div class="container">
                          <div class="row g-0">
                              <div class="col-12 col-lg-3">
                                  <div class="header-content bg-dark h-100 pt-6 pe-6 pb-6">
                                      <a href="/" title="{{logo_title}}" class="navbar-brand d-inline-flex pb-5 wow fadeInUp" data-wow-delay="0.1s">
                                          <h1 class="display-6 text-white mb-0">{{logo_text}}</h1>
                                      </a>
                                      <div class="text-start d-flex flex-column justify-content-center wow fadeInUp" data-wow-delay="0.3s">
                                          <p class="text-white sub-title">{{title_1}}</p>
                                          <h1 class="display-6 text-white mb-0">{{title_2}}</h1>
                                      </div>
                                  </div>
                              </div>
                              <div class="col-12 col-lg-9">
                                  <div class="header-img d-flex h-100 pt-6 ps-6 pb-6">
                                      <div class="row g-5">
                                          <div class="col-xl-6 wow fadeInUp" data-wow-delay="0.1s">
                                              <div class="bg-light p-4" style="border-radius: 68% 32% 100% 0% / 0% 75% 25% 100%;">
                                                  <img src="{{ glide:image preset="medium" }}" class="img-fluid w-100" style="border-radius: 68% 32% 100% 0% / 0% 75% 25% 100%;" alt="{{title_1}} {{title_2}}">
                                              </div>
                                          </div>
                                          <div class="col-xl-6 wow fadeInUp" data-wow-delay="0.3s">
                                              <h1 class="display-6 mb-4">{{heading}}</h1>
                                              <p class="mb-4">{{description}}</p>
                                              {{address}}
                                              <div class="d-flex align-items-center mb-2">
                                                  <i class="fas fa-map-marker-alt text-primary me-3"></i>
                                                  <p class="text-dark mb-0">{{text}}</p>
                                              </div>
                                             {{/address}}
                                              <div class="d-flex">
                                                  {{social_links}}
                                                  <a class="btn btn-primary btn-sm-square me-3" href="{{url}}" target="_blank"><i class="fab {{icon}} text-white"></i></a>
                                                  {{/social_links}}
                                              </div>
                                          </div>
                                      </div>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </div>
                  <!-- Header End -->
        image: images/designer-(2).jpeg
  -
    type: set
    attrs:
      id: m0ux4pi8
      values:
        type: blog_listing
        title_1: Blog
        title_2: 'Recent Posts'
        number_of_items: 8
        edit_template: true
        custom_template: |-
          <!-- Blog Start -->  
          <div class="container-fluid" id="ipersonalBlog">
              <div class="container">
                  <div class="row g-0">
                      <div class="col-lg-3">
                          <div class="blog-header h-100 bg-dark pt-6 pe-6 pb-6">
                              <div class="text-start d-flex flex-column justify-content-center wow fadeInUp"
                                  data-wow-delay="0.1s">
                                  <p class="text-white sub-title">{{title_1}}</p>
                                  <h1 class="display-6 text-white mb-0">{{title_2}}</h1>
                              </div>
                          </div>
                      </div>
                      <div class="col-lg-9">
                          <div class="blog-content h-100 pt-6 ps-6 pb-6">
                              <div class="row g-4">

                                  {{ collection:blog paginate="{{number_of_items}}" as="posts"  status:is="published" sort="date:asc"}}

                                  {{ if no_results }}
                                  <p>Aww, there are no results.</p>
                                  {{ /if }}

                                  {{ posts }}

                                  <div class="col-xl-6">
                                      <div class="blog-item wow fadeInUp" data-wow-delay="0.1s">
                                          <div class="row g-4">
                                              <div class="col-4">
                                                  <div class="blog-item-img bg-dark h-100">
                                                      <a href="#">
                                                          <img src="{{glide:image preset="portfolio"}}" class="img-fluid w-100 h-100"
                                                              style="object-fit: cover;" alt="{{title}}">
                                                      </a>
                                                  </div>
                                              </div>
                                              <div class="col-8">
                                                  <div class="h-100">
                                                      <p class="text-body mb-3"><i class="fa fa-calendar-alt me-2"></i> {{date | format('d  F Y')}}</p>
                                                      <a href="{{url}}" class="d-inline-block h4 mb-4">{{title}}</a>
                                                      <div class="py-2 px-3 bg-light d-flex justify-content-between">
                                                          <p class="mb-0 text-body">By <a href="#" class="h6">{{author.name}}</a></p>
                                                          <p class="mb-0 text-body">In <a href="#" class="h6">{{category}}</a></p>
                                                      </div>
                                                  </div>
                                              </div>
                                          </div>
                                      </div>
                                  </div>
                                  {{ /posts }}






                                 


                                  {{if more_button_text}}
                                  <div class="col-12 wow fadeInUp" data-wow-delay="0.9s">
                                      <div class="blog-btn d-flex justify-content-center">

                                          <a href="{{more_button_link}}" class="btn d-inline-block p-0">{{more_button_text}}</a>
                                      </div>
                                  </div>
                                  {{else}}
                                  {{ paginate }}
                                 <p>{{ if prev_page }} <a href="{{ prev_page }}" class="justify-content-start">⬅ Previous</a>{{/if}}&nbsp;&nbsp;&nbsp;&nbsp;{{ if next_page}}<a class="justify-content-end" href="{{ next_page }}">Next ➡</a>{{/if}}</p>
                                  {{ /paginate }}
                                  {{/if}}


                                  {{ /collection:blog }}




                              </div>
                          </div>
                      </div>
                  </div>
              </div>
          </div>
          <!-- Blog End -->
        more_button_link: /blog
  -
    type: set
    attrs:
      id: m0v29zsu
      values:
        type: contact_us
        title_1: 'Contact Me'
        title_2: 'Lets Start a New Project'
        description: 'In publishing and graphic design, Lorem ipsum is a placeholder text commonly used to demonstrate the visual form of a document or a typeface without relying on meaningful content. Lorem ipsum may be used as a placeholder before the final copy is available.'
        contact_details:
          -
            id: m0v2aaes
            icon: 'fas fa-map-marker-alt'
            title: Address
            data: India
            type: new_set
            enabled: true
          -
            id: m0v2alub
            icon: 'fas fa-map-marker-alt'
            title: Email
            data: manup.rav@gmail.com
            type: new_set
            enabled: true
        google_map_iframe: |-
          <iframe class="rounded w-100" style="height: 400px;"
                                                  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d387191.33750346623!2d-73.97968099999999!3d40.6974881!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c24fa5d33f083b%3A0xc80b8f06e177fe62!2sNew%20York%2C%20NY%2C%20USA!5e0!3m2!1sen!2sbd!4v1694259649153!5m2!1sen!2sbd"
                                                  loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        edit_template: false
        custom_template: |-
          <!-- Contact Start -->
          <div class="container-fluid" id="ipersonalContact">
              <div class="container">
                  <div class="row g-0">
                      <div class="col-lg-3">
                          <div class="contact-header h-100 bg-dark pt-6 pe-6 pb-6">
                              <div class="text-start d-flex flex-column justify-content-center wow fadeInUp"
                                  data-wow-delay="0.1s">
                                  <p class="text-white sub-title">{{title_1}}</p>
                                  <h1 class="display-6 text-white mb-0">{{title_2}}</h1>
                              </div>
                          </div>
                      </div>
                      <div class="col-lg-9">
                          <div class="contact-content h-100 pt-6 ps-6 pb-6">
                              <div class="bg-light p-4">
                                  <div class="row g-5">
                                      <div class="col-xl-5 wow fadeInUp" data-wow-delay="0.1s">
                                          <p class="mb-4">{{description}}</p>
                                          {{contact_details}}
                                          <div class="d-flex mb-4">
                                              <div class="btn-xl-square bg-primary text-white me-3">
                                                  <i class="{{icon}}"></i>
                                              </div>
                                              <div>
                                                  <h4>{{title}}</h4>
                                                  <p class="mb-0">{{data}}</p>
                                              </div>
                                          </div>
                                          {{/contact_details}}
                                      </div>
                                      <div class="col-xl-7 wow fadeInUp" data-wow-delay="0.3s">
                                          <div>
                                              {{form:contact_us}}
                                              <div class="row g-3">


                                                  {{ if success }}
                                                  <div class="text-success">
                                                      {{ form_success_message }}
                                                  </div>
                                              {{ /if }}
                                                 {{ if errors }}
                                                      <div class="text-danger mb-3">
                                                          {{ errors }}
                                                              {{ value }}<br>
                                                          {{ /errors }}
                                                      </div>
                                                  {{ /if }}



                                                  {{ fields }}
                                                  {{if type=="textarea"}}


                                                  <div class="col-12">
                                                      <div class="form-floating">
                                                          <textarea name="{{handle}}" class="form-control border-0"
                                                              placeholder="{{placeholder}}" id="{{handle}}"
                                                              style="height: 120px"></textarea>
                                                          <label for="message">{{placeholder}}</label>
                                                      </div>
                                                  </div>


                                                  {{elseif handle=="subject"}}
                                                  <div class="col-12">
                                                      <div class="form-floating">
                                                          <input type="{{type}}" class="form-control border-0" id="{{handle}}"
                                                              name="{{handle}}" placeholder="{{placeholder}}">
                                                          <label for="subject">Subject</label>
                                                      </div>
                                                  </div>
                                                  {{else}}
                                                  <div class="col-lg-12 col-xl-6">
                                                      <div class="form-floating">
                                                          <input type="{{type}}" class="form-control border-0" id="{{handle}}"
                                                              name="{{handle}}" placeholder="{{placeholder}}">
                                                          <label for="name">{{placeholder}}</label>
                                                      </div>
                                                  </div>
                                                  {{/if}}
                                                  {{ /fields }}
                                                

                                                  <div class="col-12">
                                                      <button type="submit" class="btn btn-primary w-100 py-3">Send
                                                          Message</button>
                                                  </div>
                                              </div>
                                              {{/form:contact_us}}

                                          </div>
                                      </div>
                                      <div class="col-12 wow fadeInUp" data-wow-delay="0.5s">
                                          <div class="rounded">
                                              {{google_map_iframe}}
                                          </div>
                                      </div>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </div>
              </div>
          </div>
          <!-- Contact End -->
  -
    type: paragraph
---
