<style>
  table {
    border-collapse: collapse !important;
    width: 100%;
    margin-bottom: 20px;
  }
  th, td {
    border: 1px solid #224422 !important; /* Faint matrix-green lines to match the Hacker theme */
    padding: 10px !important;
  }
  /* Force all images in the first column to be exact 60x60 pixel squares */
  td:first-child img {
    width: 300px !important;
    height: 300px !important;
    object-fit: contain !important; /* Prevents the image from stretching or distorting */
    background-color: transparent;  /* Keeps it clean on the dark background */
</style>

# My Builds
Welcome to my homelab tracking site. Click a server below to see its specific hardware specs and role:

* [Main Unraid NAS](https://username.github.io/server-1/) - Storage & Core Docker containers
* [Debian VM Host](https://username.github.io/server-2/) - High-performance virtualization
* [Backup Target OMV](https://username.github.io/server-3/) - Offsite/Secondary rsync backup
* [Network & Services](https://username.github.io/server-4/) - UniFi controller, DNS, and automation
