
<img width="1920" height="3461" alt="coffee-media-query-12-12-2025_12_23_PM" src="https://github.com/user-attachments/assets/7be6da5a-b34f-40e7-a250-7ccaa737bf39" />

☕ Coffee Shop Website

A fully responsive Coffee Shop front-end website built using HTML5 and CSS3. The project includes modern UI elements, hover effects, background images, Flexbox layouts, and media queries for responsiveness.

📸 Project Preview

A clean homepage with:

Hero background banner

Product showcase (Coffee Types)

Milkshake section

Blogs section

Smooth hover animations

Responsive layout for all screen sizes

🛠️ Technologies Used

HTML5 for structure

CSS3 for styling

Flexbox for layout alignment

Media Queries for mobile/tablet/desktop responsive design

github (url):https://github.com/ankitmor96/coffee-media-query-clone

🎨 CSS Features Used
✔ Background Images

Responsive hero section with full-width background:

.back-img {
    background-image: url(./asset/banner.jpg);
    background-size: cover;
    height: 100vh;
}
✔ Hover Effects
.box1:hover {
    box-shadow: 0 54px 55px rgba(0, 0, 0, 0.25);
}
✔ Responsive Cards

Using flex-wrap and dynamic widths:

@media (min-width: 768px) {
  .box-1 {
      gap: 3vh;
  }
}
📱 Responsive Breakpoints

The page adapts to 3 major screen sizes:

576px (Mobile)

768px (Tablet)

1440px (Laptop/Desktop)

Each breakpoint adjusts:

ul menu spacing

Image sizes

Card widths

Text alignment
