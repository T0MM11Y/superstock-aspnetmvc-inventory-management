# ASP.NET Core MVC SuperStock Inventory Management

This project explores the use of the ASP.NET Core MVC framework to develop a straightforward web application for managing product inventory in a marketplace setting. ASP.NET Core MVC is widely used for building scalable web applications, but my experience highlighted some important considerations for new developers.

While building this project with VS Code instead of the full Microsoft Visual Studio IDE, I found the debugging process to be slower and less efficient. Additionally, package management within this framework often felt sluggish, especially compared to more familiar environments like React or Laravel. For those interested in mastering MVC concepts, ASP.NET Core MVC offers valuable insights. However, for large-scale applications or rapid development cycles, alternative frameworks may prove more efficient.

<p align="center">
  <img src="https://github.com/T0MM11Y/ASP.NET-MVC-SuperStock/blob/main/gambar/login.png?raw=true" width="400"/>
</p>

---

## User Roles & Permissions

**Sellers:**
- Can add new products to the inventory.
- Can edit or delete only their own products.
- Cannot modify or remove products belonging to other sellers.

**Admins:**
- Can add new sellers to the platform.
- Can add new product categories.
- Cannot add or edit products directly.
- Can delete any product from the inventory.

---

<p align="center">
  <img src="https://github.com/T0MM11Y/ASP.NET-MVC-SuperStock/blob/main/gambar/dashboard.png?raw=true" width="400"/>
  <img src="https://github.com/T0MM11Y/ASP.NET-MVC-SuperStock/blob/main/gambar/product.png?raw=true" width="400"/>
</p>
