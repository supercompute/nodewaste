---
title: Home
sections:
- type: heroblock
  template: heroblock
  section_id: hero
  title: Welcome to Node Waste
  component: hero_block.html
  content: An iot zero waste solution
  image: images/hero.png
  actions:
  - label: Learn More
    url: "/features"
- type: featuresblock
  template: featuresblock
  section_id: features
  title: Features
  component: features_block.html
  subtitle: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam a metus
    quis lorem malesuada luctus.
  bg: gray
  featureslist:
  - title: Waste Diversion
    content: Diverting waste _from_ landfills
    image: images/feature1.png
    actions:
    - label: Learn More
      url: "/features"
  - title: Visualization
    content: Have a real look at what the recycling economy looks like in your area
    image: images/feature2.png
    actions:
    - label: Learn More
      url: "/features"
  - title: Reduce Contamination
    content: Presort your waste at home
    image: images/feature3.png
    actions:
    - label: Learn More
      url: "/features"
- type: reviewsblock
  template: reviewsblock
  section_id: reviews
  title: Testimonials
  component: reviews_block.html
  subtitle: 'Aliquam malesuada ligula eget est fringilla blandit. Integer finibus
    semper libero id sodales. '
  bg: white
  reviews:
  - author: John Doe
    avatar: images/review1.jpg
    content: Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis nunc
      non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
  - author: Jane Roe
    avatar: images/review2.jpg
    content: Sed laoreet magna commodo libero euismod sodales. Nunc ac libero convallis,
      interdum ligula vel, pretium diam. Integer commodo sem at dui sollicitudin,
      vel posuere justo laoreet.
  - author: Richard Roe
    avatar: images/review3.jpg
    content: Integer consectetur purus neque, ac porttitor enim convallis vitae. Interdum
      et malesuada fames ac ante ipsum primis in faucibus.
- type: ctablock
  template: ctablock
  section_id: call-to-action
  title: This Is Call To Action Block!
  component: cta_block.html
  subtitle: This is an optional description for the call to action block.
  actions:
  - label: Get Started
    url: "/signup"
- type: postsblock
  template: postsblock
  section_id: recent-posts
  title: Latest Posts
  component: posts_block.html
  bg: gray
  subtitle: ''
layout: home
menu:
  main:
    weight: 1

---
