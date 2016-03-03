Polymer is all about speed, modern browsers and web components.
Polymer 1.0 uses the shady DOM system and decreases the size of polyfill needed to run on browsers that don't support shadow DOM natively.
The PSK’s design pattern for structuring pages is to make each page a <section> element. The<iron-pages> element controls which page is displayed at any given time.
The data-route attribute is an identifier for the routing system. You’ll set that up for your new page in the next section.
The <paper-material> element creates a card which floats on top of the main content area. If you want to follow the Material Design specification, all main content should be displayed on top of one of these cards.
The elevation attribute determines how high a <paper-material> element appears to visually float above the main content area. Experiment by setting it to values between 0 and 5.
{{ title }} {{ lastName }} Polymer uses binding.