B_K ONLINE SHOPPING - PRIVATE STOREFRONT UPDATE

WHAT CHANGED:
- Removed the Owner Control/Admin Control link from the public navigation.
- Removed the owner/admin dashboard section from the public storefront page.
- Kept customer-facing shopping, TikTok, wishlist, coupon preview, review preview,
  WhatsApp settings, shopping helper, cart, checkout and order tracking sections.
- Added a clean public footer.

IMPORTANT SECURITY NOTE:
This update hides the admin panel from the public storefront. It does NOT create secure
administrator authentication. A static GitHub Pages website cannot protect private admin
data or actions by hiding a link or HTML section. Before using real customer data, payments,
or inventory, the admin dashboard must be moved behind secure server-side authentication
and database access rules (for example, Supabase Auth + Row Level Security).
