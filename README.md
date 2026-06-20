Create a complete used-book inventory and sales website from the uploaded bookshelf images.

Requirements:

1. Detect and identify every visible book.
2. Extract each book into a separate image file.
3. Generate a book inventory list with:

   * Book ID (B001, B002, ...)
   * Book Name
   * Author (if visible)
   * Category
   * Random Price between $5 and $9
4. Create a responsive HTML/CSS/JavaScript webpage.

Webpage Features:

* Display book image, title, and price.
* Search box with autocomplete suggestions.
* Shopping cart.
* Add/Remove books from cart.
* Calculate totals automatically.
* Generate unique receipt number for each sale.
* Include sale date and time.
* Generate QR code on receipt containing:

  * Receipt ID
  * Date
  * Time
  * Total Amount
* Print receipt.
* Download receipt as PNG image.
* Email receipt using mailto.
* Send receipt by SMS using sms link.
* Maintain sold-book inventory.

Inventory Rules:

* Each book is unique (quantity = 1).
* When a book is sold:

  * Remove it from inventory.
  * Remove it from search/autocomplete.
  * Update sold count.
  * Prevent future purchase.
* Display available books only.

Output Files:

1. Individual book images.
2. Complete inventory CSV.
3. HTML webpage.
4. ZIP containing all files.

Optional Enhancements:

* Store sold inventory in localStorage.
* Restore inventory after browser refresh.
* Export daily sales report CSV.
* Generate barcode and QR code for each book.
* Dashboard showing:

  * Total Books
  * Available Books
  * Sold Books
  * Revenue
  * Today's Sales
* Mobile-friendly POS layout.

Use the uploaded images as the source inventory.
