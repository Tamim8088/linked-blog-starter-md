/yacht-project
│
├── /admin                  # (Future CMS Backend)
│   ├── index.php           # Dashboard
│   ├── login.php
│   ├── listings.php        # Manage yachts
│   └── posts.php           # Manage blog
│
├── /assets
│   ├── /css
│   │   ├── input.css       # Tailwind source
│   │   └── style.css       # Compiled Tailwind output
│   ├── /images             # Static site images (logos, icons)
│   └── /js
│       └── main.js
│
├── /config
│   ├── db.php              # Database connection
│   └── functions.php       # Helper PHP functions
│
├── /includes               # Reusable UI components
│   ├── header.php
│   ├── footer.php
│   ├── navbar.php
│   └── yacht-card.php
│
├── /uploads                # (CMS Storage)
│   ├── /yachts             # Dynamic yacht images
│   └── /blog               # Dynamic blog thumbnails
│
├── index.php               # Homepage
├── listing.php             # All yachts grid
├── yacht-profile.php       # Single yacht detail page
├── blog.php                # Blog feed
├── post.php                # Single blog post
├── contact.php
│
├── package.json            # Tailwind dependencies
└── tailwind.config.js      # Tailwind configuration