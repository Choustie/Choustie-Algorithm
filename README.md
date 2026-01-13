# Choustie Algorithm

O(1) collision detection via progress-state indexing.

## What is this?

A method for detecting intersections between moving entities in constant time, regardless of entity count.

Traditional collision detection: O(n²) or O(n log n)
This: O(1)

## How it works

Instead of indexing by position and checking across time, index by position AND progress state simultaneously.

Entities that will collide are already neighbors in the index at insertion time.

## Patent

Patent pending: SE 2630027-7 (Swedish Patent and Registration Office)

## License

Free for individuals and organizations with revenue under $100,000 USD.

Commercial use above this threshold requires a license.

See [LICENSE.txt](LICENSE.txt) for full terms.

**[Purchase commercial license](https://buy.stripe.com/00wbJ1eRx0gz8NvbPXdQQ00)**

**Contact:** Choustie-Algorithm@protonmail.com
