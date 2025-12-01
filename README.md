# startbootstrap-sb-Tubes-1
TUBES DAP KELOMPOK 1
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Museum Bandung - Sistem Integrasi Informasi Museum Cerdas</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header -->
    <header class="header">
        <div class="container">
            <div class="header-content">
                <div class="brand">
                    <div class="brand-icon">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <rect width="16" height="20" x="4" y="2" rx="2" ry="2"></rect>
                            <path d="M9 22v-4h6v4"></path>
                            <path d="M8 6h.01"></path>
                            <path d="M16 6h.01"></path>
                            <path d="M12 6h.01"></path>
                            <path d="M12 10h.01"></path>
                            <path d="M12 14h.01"></path>
                            <path d="M16 10h.01"></path>
                            <path d="M16 14h.01"></path>
                            <path d="M8 10h.01"></path>
                            <path d="M8 14h.01"></path>
                        </svg>
                    </div>
                    <div>
                        <h1>Museum Bandung</h1>
                        <p>Jelajahi Warisan Budaya</p>
                    </div>
                </div>

                <nav class="nav-desktop">
                    <a href="#home">Beranda</a>
                    <a href="#museums">Semua Museum</a>
                    <a href="#about">Tentang</a>
                    <button class="btn-primary">Hubungi Kami</button>
                </nav>

                <button class="menu-toggle" id="menuToggle">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <line x1="3" y1="12" x2="21" y2="12"></line>
                        <line x1="3" y1="6" x2="21" y2="6"></line>
                        <line x1="3" y1="18" x2="21" y2="18"></line>
                    </svg>
                </button>
            </div>

            <nav class="nav-mobile" id="mobileNav">
                <a href="#home">Beranda</a>
                <a href="#museums">Semua Museum</a>
                <a href="#about">Tentang</a>
                <button class="btn-primary">Hubungi Kami</button>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-background"></div>
        <div class="container">
            <div class="hero-grid">
                <div class="hero-content">
                    <div class="hero-badge">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M20 10c0 6-8 12-8 12s-8-6-8-12a8 8 0 0 1 16 0Z"></path>
                            <circle cx="12" cy="10" r="3"></circle>
                        </svg>
                        <span>Kota Bandung, Jawa Barat</span>
                    </div>

                    <h2 class="hero-title">Portal Museum Bandung</h2>
                    <p class="hero-description">
                        Jelajahi kekayaan sejarah, budaya, dan seni melalui berbagai museum 
                        di Kota Bandung. Temukan pengalaman edukatif dan inspiratif di setiap sudutnya.
                    </p>

                    <div class="search-box">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <circle cx="11" cy="11" r="8"></circle>
                            <path d="m21 21-4.3-4.3"></path>
                        </svg>
                        <input type="text" id="heroSearch" placeholder="Cari museum berdasarkan nama atau kategori...">
                    </div>

                    <div class="hero-buttons">
                        <button class="btn-primary" onclick="document.getElementById('museums').scrollIntoView({behavior: 'smooth'})">
                            Jelajahi Semua Museum
                        </button>
                        <button class="btn-secondary">Lihat Peta</button>
                    </div>
                </div>

                <div class="hero-images">
                    <div class="hero-images-grid">
                        <div class="hero-images-col">
                            <div class="hero-image">
                                <img src="https://images.unsplash.com/photo-1686987195191-b3f91321d37d?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3Nzg4Nzd8MHwxfHNlYXJjaHwxfHxnZW9sb2d5JTIwbXVzZXVtJTIwaW5kb25lc2lhfGVufDF8fHx8MTc2NDU1ODQ5N3ww&ixlib=rb-4.1.0&q=80&w=400" alt="Museum">
                            </div>
                            <div class="hero-image hero-image-small">
                                <img src="https://images.unsplash.com/photo-1643820509303-79e98ac7e006?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3Nzg4Nzd8MHwxfHNlYXJjaHwxfHxhcnQlMjBnYWxsZXJ5JTIwbXVzZXVtfGVufDF8fHx8MTc2NDUyNzUyM3ww&ixlib=rb-4.1.0&q=80&w=400" alt="Museum">
                            </div>
                        </div>
                        <div class="hero-images-col hero-images-col-offset">
                            <div class="hero-image hero-image-small">
                                <img src="https://images.unsplash.com/photo-1706264568861-81855ecf51a8?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3Nzg4Nzd8MHwxfHNlYXJjaHwxfHxhc2lhbiUyMGFmcmljYW4lMjBjb25mZXJlbmNlJTIwYnVpbGRpbmd8ZW58MXx8fHwxNzY0NTU4NDk4fDA&ixlib=rb-4.1.0&q=80&w=400" alt="Museum">
                            </div>
                            <div class="hero-image">
                                <img src="https://images.unsplash.com/photo-1680144653445-9ea91934e5d1?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3Nzg4Nzd8MHwxfHNlYXJjaHwxfHx0cmFkaXRpb25hbCUyMGluZG9uZXNpYW4lMjBtdXNldW18ZW58MXx8fHwxNzY0NTU4NDk4fDA&ixlib=rb-4.1.0&q=80&w=400" alt="Museum">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="stats">
        <div class="container">
            <div class="stats-grid">
                <div class="stat-item">
                    <div class="stat-icon">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <rect width="16" height="20" x="4" y="2" rx="2" ry="2"></rect>
                            <path d="M9 22v-4h6v4"></path>
                        </svg>
                    </div>
                    <div class="stat-value">8+</div>
                    <div class="stat-label">Museum Terdaftar</div>
                </div>
                <div class="stat-item">
                    <div class="stat-icon">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2"></path>
                            <circle cx="9" cy="7" r="4"></circle>
                            <path d="M22 21v-2a4 4 0 0 0-3-3.87"></path>
                            <path d="M16 3.13a4 4 0 0 1 0 7.75"></path>
                        </svg>
                    </div>
                    <div class="stat-value">500K+</div>
                    <div class="stat-label">Pengunjung/Tahun</div>
                </div>
                <div class="stat-item">
                    <div class="stat-icon">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <rect width="18" height="18" x="3" y="4" rx="2" ry="2"></rect>
                            <line x1="16" y1="2" x2="16" y2="6"></line>
                            <line x1="8" y1="2" x2="8" y2="6"></line>
                            <line x1="3" y1="10" x2="21" y2="10"></line>
                        </svg>
                    </div>
                    <div class="stat-value">Sejak 1928</div>
                    <div class="stat-label">Museum Tertua</div>
                </div>
                <div class="stat-item">
                    <div class="stat-icon">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <circle cx="12" cy="8" r="6"></circle>
                            <path d="M15.477 12.89 17 22l-5-3-5 3 1.523-9.11"></path>
                        </svg>
                    </div>
                    <div class="stat-value">10+</div>
                    <div class="stat-label">Koleksi Langka</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Museums Section -->
    <section id="museums" class="museums">
        <div class="container">
            <div class="section-header">
                <h2>Jelajahi Museum</h2>
                <p>Temukan berbagai museum menarik di Bandung dengan koleksi yang beragam</p>
            </div>

            <!-- Search and Filter -->
            <div class="museums-controls">
                <div class="search-box">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <circle cx="11" cy="11" r="8"></circle>
                        <path d="m21 21-4.3-4.3"></path>
                    </svg>
                    <input type="text" id="museumSearch" placeholder="Cari museum...">
                </div>

                <div class="filter-buttons" id="filterButtons">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <polygon points="22 3 2 3 10 12.46 10 19 14 21 14 12.46 22 3"></polygon>
                    </svg>
                    
                </div>
            </div>

            <!-- Museum Grid -->
            <div class="museum-grid" id="museumGrid">
                <!-- Museum cards will be generated by JavaScript -->
            </div>
        </div>
    </section>

    <!-- Museum Detail Modal -->
    <div class="modal" id="museumModal">
        <div class="modal-content">
            <div class="modal-header">
                <img id="modalImage" src="" alt="">
                <div class="modal-header-overlay">
                    <button class="btn-back" id="closeModal">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <line x1="19" y1="12" x2="5" y2="12"></line>
                            <polyline points="12 19 5 12 12 5"></polyline>
                        </svg>
                        Kembali
                    </button>
                    <div class="modal-header-info">
                        <div class="modal-category" id="modalCategory"></div>
                        <h2 id="modalName"></h2>
                        <div class="modal-address">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <path d="M20 10c0 6-8 12-8 12s-8-6-8-12a8 8 0 0 1 16 0Z"></path>
                                <circle cx="12" cy="10" r="3"></circle>
                            </svg>
                            <span id="modalAddress"></span>
                        </div>
                    </div>
                </div>
            </div>

            <div class="modal-body">
                <div class="modal-main">
                    <div class="modal-section">
                        <h3>Tentang Museum</h3>
                        <p id="modalDescription"></p>
                    </div>

                    <div class="modal-section">
                        <h3>Fasilitas</h3>
                        <div class="facilities-grid" id="modalFacilities"></div>
                    </div>

                    <div class="modal-section">
                        <h3>Lokasi</h3>
                        <div class="map-placeholder">
                            <svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <path d="M20 10c0 6-8 12-8 12s-8-6-8-12a8 8 0 0 1 16 0Z"></path>
                                <circle cx="12" cy="10" r="3"></circle>
                            </svg>
                            <p>Peta Lokasi</p>
                            <p class="coordinates" id="modalCoordinates"></p>
                        </div>
                    </div>
                </div>

                <div class="modal-sidebar">
                    <div class="info-card">
                        <h3>Informasi Kunjungan</h3>
                        
                        <div class="info-item">
                            <div class="info-icon">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <circle cx="12" cy="12" r="10"></circle>
                                    <polyline points="12 6 12 12 16 14"></polyline>
                                </svg>
                            </div>
                            <div>
                                <div class="info-title">Jam Operasional</div>
                                <p id="modalHours"></p>
                            </div>
                        </div>

                        <div class="info-item">
                            <div class="info-icon">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M2 9a3 3 0 0 1 0 6v2a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2v-2a3 3 0 0 1 0-6V7a2 2 0 0 0-2-2H4a2 2 0 0 0-2 2Z"></path>
                                    <path d="M13 5v2"></path>
                                    <path d="M13 17v2"></path>
                                    <path d="M13 11v2"></path>
                                </svg>
                            </div>
                            <div>
                                <div class="info-title">Harga Tiket</div>
                                <p id="modalPrice"></p>
                            </div>
                        </div>

                        <div class="info-item">
                            <div class="info-icon">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"></path>
                                </svg>
                            </div>
                            <div>
                                <div class="info-title">Kontak</div>
                                <p id="modalPhone"></p>
                            </div>
                        </div>

                        <div id="websiteButton"></div>

                        <button class="btn-secondary btn-full">Buka di Maps</button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-grid">
                <div class="footer-column">
                    <div class="footer-brand">
                        <div class="brand-icon">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <rect width="16" height="20" x="4" y="2" rx="2" ry="2"></rect>
                                <path d="M9 22v-4h6v4"></path>
                            </svg>
                        </div>
                        <h3>Museum Bandung</h3>
                    </div>
                    <p>Portal informasi lengkap museum-museum di Kota Bandung</p>
                </div>

                <div class="footer-column">
                    <h4>Quick Links</h4>
                    <ul>
                        <li><a href="#home">Beranda</a></li>
                        <li><a href="#museums">Semua Museum</a></li>
                        <li><a href="#about">Tentang Kami</a></li>
                        <li><a href="#contact">Kontak</a></li>
                    </ul>
                </div>

                <div class="footer-column">
                    <h4>Kategori</h4>
                    <ul>
                        <li><a href="#">Sejarah</a></li>
                        <li><a href="#">Seni & Budaya</a></li>
                        <li><a href="#">Sains & Teknologi</a></li>
                        <li><a href="#">Militer</a></li>
                    </ul>
                </div>

                <div class="footer-column">
                    <h4>Kontak Kami</h4>
                    <ul class="contact-list">
                        <li>
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <path d="M20 10c0 6-8 12-8 12s-8-6-8-12a8 8 0 0 1 16 0Z"></path>
                                <circle cx="12" cy="10" r="3"></circle>
                            </svg>
                            Bandung, Jawa Barat
                        </li>
                        <li>
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"></path>
                            </svg>
                            (022) 1234567
                        </li>
                        <li>
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <rect width="20" height="16" x="2" y="4" rx="2"></rect>
                                <path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"></path>
                            </svg>
                            info@museumbandung.id
                        </li>
                    </ul>
                </div>
            </div>

            <div class="footer-bottom">
                <p>&copy; 2024 Museum Bandung. All rights reserved.</p>
                <div class="social-links">
                    <a href="#" class="social-link">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
                            <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path>
                            <line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line>
                        </svg>
                    </a>
                    <a href="#" class="social-link">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"></path>
                        </svg>
                    </a>
                    <a href="#" class="social-link">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M22 4s-.7 2.1-2 3.4c1.6 10-9.4 17.3-18 11.6 2.2.1 4.4-.6 6-2C3 15.5.5 9.6 3 5c2.2 2.6 5.6 4.1 9 4-.9-4.2 4-6.6 7-3.8 1.1 0 3-1.2 3-1.2z"></path>
                        </svg>
                    </a>
                </div>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>




/* Reset & Base Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

:root {
  --amber-50: #fffbeb;
  --amber-100: #fef3c7;
  --amber-200: #fde68a;
  --amber-300: #fcd34d;
  --amber-400: #fbbf24;
  --amber-600: #d97706;
  --amber-700: #b45309;
  --amber-800: #92400e;
  --amber-900: #78350f;
  --orange-600: #ea580c;
  --orange-900: #7c2d12;
  --white: #ffffff;
  --transition: all 0.3s ease;
}

body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen', 'Ubuntu', 'Cantarell', sans-serif;
  line-height: 1.6;
  color: var(--amber-900);
  background-color: var(--amber-50);
  overflow-x: hidden;
}

.container {
  max-width: 1280px;
  margin: 0 auto;
  padding: 0 1.5rem;
}

h1 {
  font-size: 1.25rem;
  font-weight: 600;
  line-height: 1.5;
}

h2 {
  font-size: 2.25rem;
  font-weight: 600;
  line-height: 1.4;
  margin-bottom: 1rem;
}

h3 {
  font-size: 1.5rem;
  font-weight: 600;
  line-height: 1.5;
  margin-bottom: 0.75rem;
}

h4 {
  font-size: 1.125rem;
  font-weight: 600;
  line-height: 1.5;
}

p {
  font-size: 1rem;
  line-height: 1.6;
}

/* Header */
.header {
  position: sticky;
  top: 0;
  z-index: 50;
  background-color: rgba(255, 255, 255, 0.9);
  backdrop-filter: blur(12px);
  border-bottom: 1px solid var(--amber-200);
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
}

.header-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1rem 0;
}

.brand {
  display: flex;
  align-items: center;
  gap: 0.75rem;
}

.brand-icon {
  width: 2.5rem;
  height: 2.5rem;
  background: linear-gradient(135deg, var(--amber-600), var(--orange-600));
  border-radius: 0.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
}

.brand h1 {
  color: var(--amber-900);
  margin: 0;
}

.brand p {
  font-size: 0.875rem;
  color: var(--amber-700);
  margin: 0;
}

.nav-desktop {
  display: none;
  align-items: center;
  gap: 2rem;
}

.nav-desktop a {
  color: var(--amber-900);
  text-decoration: none;
  font-weight: 500;
  transition: var(--transition);
}

.nav-desktop a:hover {
  color: var(--amber-600);
}

.menu-toggle {
  display: block;
  background: none;
  border: none;
  color: var(--amber-900);
  cursor: pointer;
  padding: 0.5rem;
}

.nav-mobile {
  display: none;
  flex-direction: column;
  gap: 1rem;
  padding: 1rem 0 0.5rem;
}

.nav-mobile.active {
  display: flex;
}

.nav-mobile a {
  color: var(--amber-900);
  text-decoration: none;
  font-weight: 500;
  transition: var(--transition);
}

.nav-mobile a:hover {
  color: var(--amber-600);
}

@media (min-width: 768px) {
  .nav-desktop {
    display: flex;
  }
  
  .menu-toggle {
    display: none;
  }
  
  .nav-mobile {
    display: none !important;
  }
}

/* Buttons */
.btn-primary {
  padding: 0.75rem 1.5rem;
  background: linear-gradient(135deg, var(--amber-600), var(--orange-600));
  color: white;
  border: none;
  border-radius: 0.5rem;
  font-weight: 600;
  cursor: pointer;
  transition: var(--transition);
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.btn-primary:hover {
  box-shadow: 0 10px 15px rgba(217, 119, 6, 0.3);
  transform: translateY(-2px);
}

.btn-secondary {
  padding: 0.75rem 1.5rem;
  background: white;
  color: var(--amber-900);
  border: 2px solid var(--amber-300);
  border-radius: 0.5rem;
  font-weight: 600;
  cursor: pointer;
  transition: var(--transition);
}

.btn-secondary:hover {
  background: var(--amber-50);
}

.btn-full {
  width: 100%;
}

.btn-back {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.5rem 1rem;
  background: rgba(255, 255, 255, 0.9);
  backdrop-filter: blur(4px);
  border: none;
  border-radius: 0.5rem;
  color: var(--amber-900);
  font-weight: 600;
  cursor: pointer;
  transition: var(--transition);
}

.btn-back:hover {
  background: white;
}

/* Hero Section */
.hero {
  position: relative;
  overflow: hidden;
  background: linear-gradient(135deg, var(--amber-100), #fed7aa, var(--amber-50));
  padding: 5rem 0;
}

.hero-background {
  position: absolute;
  inset: 0;
  opacity: 0.05;
  background-image: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cpath d='M36 18c3.314 0 6 2.686 6 6s-2.686 6-6 6-6-2.686-6-6 2.686-6 6-6z' stroke='%23713f12'/%3E%3C/g%3E%3C/svg%3E");
}

.hero-grid {
  position: relative;
  display: grid;
  grid-template-columns: 1fr;
  gap: 3rem;
  align-items: center;
}

.hero-badge {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  background: rgba(251, 191, 36, 0.3);
  padding: 0.5rem 1rem;
  border-radius: 9999px;
  margin-bottom: 1.5rem;
  color: var(--amber-700);
}

.hero-title {
  font-size: 2.5rem;
  color: var(--amber-900);
  margin-bottom: 1.5rem;
  line-height: 1.2;
}

.hero-description {
  color: var(--amber-800);
  font-size: 1.125rem;
  margin-bottom: 2rem;
  max-width: 32rem;
}

.search-box {
  position: relative;
  width: 100%;
  max-width: 32rem;
  margin-bottom: 1.5rem;
}

.search-box svg {
  position: absolute;
  left: 1rem;
  top: 50%;
  transform: translateY(-50%);
  color: var(--amber-600);
}

.search-box input {
  width: 100%;
  padding: 1rem 1rem 1rem 3rem;
  background: white;
  border: 2px solid var(--amber-200);
  border-radius: 0.75rem;
  font-size: 1rem;
  color: var(--amber-900);
  outline: none;
  transition: var(--transition);
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.07);
}

.search-box input:focus {
  border-color: var(--amber-600);
  box-shadow: 0 0 0 3px rgba(217, 119, 6, 0.1);
}

.search-box input::placeholder {
  color: var(--amber-400);
}

.hero-buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
}

.hero-images {
  position: relative;
}

.hero-images::before {
  content: '';
  position: absolute;
  inset: 0;
  background: linear-gradient(135deg, var(--amber-600), var(--orange-600));
  border-radius: 1.5rem;
  filter: blur(60px);
  opacity: 0.2;
}

.hero-images-grid {
  position: relative;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1rem;
}

.hero-images-col {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.hero-images-col-offset {
  padding-top: 2rem;
}

.hero-image {
  aspect-ratio: 1;
  border-radius: 1rem;
  overflow: hidden;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
}

.hero-image-small {
  aspect-ratio: 16/9;
}

.hero-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.5s ease;
}

.hero-image:hover img {
  transform: scale(1.1);
}

@media (min-width: 768px) {
  .hero-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .hero-title {
    font-size: 3rem;
  }
}

/* Stats Section */
.stats {
  background: white;
  border-top: 1px solid var(--amber-200);
  border-bottom: 1px solid var(--amber-200);
  padding: 3rem 0;
}

.stats-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
}

.stat-item {
  text-align: center;
}

.stat-icon {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 3rem;
  height: 3rem;
  background: linear-gradient(135deg, var(--amber-100), #fed7aa);
  border-radius: 0.75rem;
  margin-bottom: 0.75rem;
  color: var(--amber-600);
}

.stat-value {
  font-size: 1.875rem;
  font-weight: 600;
  color: var(--amber-900);
  margin-bottom: 0.25rem;
}

.stat-label {
  font-size: 0.875rem;
  color: var(--amber-700);
}

@media (min-width: 768px) {
  .stats-grid {
    grid-template-columns: repeat(4, 1fr);
  }
}

/* Museums Section */
.museums {
  padding: 4rem 0;
}

.section-header {
  text-align: center;
  margin-bottom: 3rem;
}

.section-header h2 {
  color: var(--amber-900);
}

.section-header p {
  color: var(--amber-700);
  max-width: 32rem;
  margin: 0 auto;
}

.museums-controls {
  margin-bottom: 2rem;
}

.museums-controls .search-box {
  max-width: 100%;
  margin-bottom: 1rem;
}

.filter-buttons {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  overflow-x: auto;
  padding-bottom: 0.5rem;
}

.filter-buttons svg {
  flex-shrink: 0;
  color: var(--amber-600);
}

.filter-btn {
  padding: 0.5rem 1rem;
  border-radius: 0.5rem;
  white-space: nowrap;
  transition: var(--transition);
  border: none;
  cursor: pointer;
  font-weight: 500;
  font-size: 0.875rem;
}

.filter-btn.active {
  background: linear-gradient(135deg, var(--amber-600), var(--orange-600));
  color: white;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.filter-btn:not(.active) {
  background: white;
  color: var(--amber-900);
  border: 2px solid var(--amber-200);
}

.filter-btn:not(.active):hover {
  background: var(--amber-50);
}

/* Museum Grid */
.museum-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 1.5rem;
}

.museum-card {
  background: white;
  border-radius: 1rem;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: var(--transition);
  cursor: pointer;
}

.museum-card:hover {
  box-shadow: 0 20px 25px rgba(0, 0, 0, 0.15);
  transform: translateY(-8px);
}

.museum-card-image {
  position: relative;
  height: 12rem;
  overflow: hidden;
}

.museum-card-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.5s ease;
}

.museum-card:hover .museum-card-image img {
  transform: scale(1.1);
}

.museum-category {
  position: absolute;
  top: 1rem;
  right: 1rem;
  background: var(--amber-600);
  color: white;
  padding: 0.25rem 0.75rem;
  border-radius: 9999px;
  font-size: 0.875rem;
  font-weight: 600;
}

.museum-card-content {
  padding: 1.5rem;
}

.museum-card-content h3 {
  color: var(--amber-900);
  margin-bottom: 0.5rem;
  transition: var(--transition);
}

.museum-card:hover .museum-card-content h3 {
  color: var(--amber-600);
}

.museum-description {
  color: var(--amber-700);
  margin-bottom: 1rem;
  display: -webkit-box;
  -webkit-line-clamp: 2;
  -webkit-box-orient: vertical;
  overflow: hidden;
}

.museum-info {
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
}

.info-row {
  display: flex;
  align-items: flex-start;
  gap: 0.5rem;
  color: var(--amber-600);
  font-size: 0.875rem;
}

.info-row svg {
  flex-shrink: 0;
  margin-top: 0.125rem;
}

.info-text {
  overflow: hidden;
  text-overflow: ellipsis;
  display: -webkit-box;
  -webkit-line-clamp: 1;
  -webkit-box-orient: vertical;
}

.museum-card-button {
  margin-top: 1rem;
  width: 100%;
  padding: 0.5rem;
  background: linear-gradient(135deg, var(--amber-600), var(--orange-600));
  color: white;
  border: none;
  border-radius: 0.5rem;
  font-weight: 600;
  cursor: pointer;
  opacity: 0;
  transition: var(--transition);
}

.museum-card:hover .museum-card-button {
  opacity: 1;
}

@media (min-width: 768px) {
  .museum-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (min-width: 1024px) {
  .museum-grid {
    grid-template-columns: repeat(3, 1fr);
  }
}

/* Modal */
.modal {
  display: none;
  position: fixed;
  inset: 0;
  background: rgba(0, 0, 0, 0.5);
  z-index: 100;
  overflow-y: auto;
}

.modal.active {
  display: block;
}

.modal-content {
  min-height: 100vh;
  background: var(--amber-50);
}

.modal-header {
  position: relative;
  height: 25rem;
  overflow: hidden;
}

.modal-header img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.modal-header-overlay {
  position: absolute;
  inset: 0;
  background: linear-gradient(to top, rgba(0, 0, 0, 0.6), transparent);
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  padding: 1.5rem;
  color: white;
}

.modal-header-info {
  color: white;
}

.modal-category {
  display: inline-block;
  background: var(--amber-600);
  padding: 0.25rem 0.75rem;
  border-radius: 9999px;
  font-size: 0.875rem;
  margin-bottom: 0.75rem;
}

.modal-header h2 {
  color: white;
  margin-bottom: 0.5rem;
}

.modal-address {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  color: var(--amber-100);
}

.modal-body {
  max-width: 1280px;
  margin: 0 auto;
  padding: 3rem 1.5rem;
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
}

.modal-main {
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

.modal-section {
  background: white;
  border-radius: 1rem;
  padding: 2rem;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.modal-section h3 {
  color: var(--amber-900);
  margin-bottom: 1rem;
}

.modal-section p {
  color: var(--amber-800);
  line-height: 1.7;
}

.facilities-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1rem;
}

.facility-item {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  padding: 0.75rem;
  background: var(--amber-50);
  border-radius: 0.5rem;
}

.facility-icon {
  width: 2rem;
  height: 2rem;
  background: linear-gradient(135deg, var(--amber-600), var(--orange-600));
  border-radius: 0.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
  color: white;
}

.facility-name {
  font-size: 0.875rem;
  color: var(--amber-900);
}

.map-placeholder {
  aspect-ratio: 16/9;
  background: linear-gradient(135deg, var(--amber-100), #fed7aa);
  border-radius: 0.75rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  color: var(--amber-600);
}

.map-placeholder p {
  color: var(--amber-800);
  margin: 0.5rem 0 0;
}

.coordinates {
  color: var(--amber-600);
  font-size: 0.875rem;
}

.modal-sidebar {
  position: sticky;
  top: 1.5rem;
  height: fit-content;
}

.info-card {
  background: white;
  border-radius: 1rem;
  padding: 1.5rem;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.info-card h3 {
  color: var(--amber-900);
  margin-bottom: 1.5rem;
}

.info-item {
  display: flex;
  align-items: flex-start;
  gap: 0.75rem;
  margin-bottom: 1rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid var(--amber-100);
}

.info-item:last-of-type {
  border-bottom: none;
}

.info-icon {
  width: 2.5rem;
  height: 2.5rem;
  background: var(--amber-100);
  border-radius: 0.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
  color: var(--amber-600);
}

.info-title {
  font-weight: 600;
  color: var(--amber-900);
  margin-bottom: 0.25rem;
  font-size: 0.875rem;
}

.info-item p {
  color: var(--amber-700);
  font-size: 0.875rem;
  margin: 0;
}

#websiteButton {
  padding-top: 1rem;
  border-top: 1px solid var(--amber-200);
  margin-bottom: 1rem;
}

@media (min-width: 1024px) {
  .modal-body {
    grid-template-columns: 2fr 1fr;
  }
  
  .facilities-grid {
    grid-template-columns: repeat(3, 1fr);
  }
}

/* Footer */
.footer {
  background: linear-gradient(135deg, var(--amber-900), var(--orange-900));
  color: white;
  padding: 3rem 0;
}

.footer-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
  margin-bottom: 2rem;
}

.footer-brand {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  margin-bottom: 1rem;
}

.footer-brand .brand-icon {
  background: rgba(255, 255, 255, 0.1);
  backdrop-filter: blur(4px);
}

.footer-brand h3 {
  color: white;
  margin: 0;
}

.footer-column p {
  color: var(--amber-200);
  font-size: 0.875rem;
}

.footer-column h4 {
  color: white;
  margin-bottom: 1rem;
}

.footer-column ul {
  list-style: none;
}

.footer-column ul li {
  margin-bottom: 0.5rem;
}

.footer-column a {
  color: var(--amber-200);
  text-decoration: none;
  transition: var(--transition);
  font-size: 0.875rem;
}

.footer-column a:hover {
  color: white;
}

.contact-list li {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  color: var(--amber-200);
  font-size: 0.875rem;
}

.footer-bottom {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1rem;
  padding-top: 2rem;
  border-top: 1px solid rgba(255, 255, 255, 0.1);
}

.footer-bottom p {
  color: var(--amber-200);
  font-size: 0.875rem;
}

.social-links {
  display: flex;
  gap: 1rem;
}

.social-link {
  width: 2.5rem;
  height: 2.5rem;
  background: rgba(255, 255, 255, 0.1);
  backdrop-filter: blur(4px);
  border-radius: 9999px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  transition: var(--transition);
}

.social-link:hover {
  background: rgba(255, 255, 255, 0.2);
}

@media (min-width: 768px) {
  .footer-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .footer-bottom {
    flex-direction: row;
    justify-content: space-between;
  }
}

@media (min-width: 1024px) {
  .footer-grid {
    grid-template-columns: repeat(4, 1fr);
  }
}

/* Utilities */
.hidden {
  display: none !important;
}

/* Scrollbar Styling */
::-webkit-scrollbar {
  width: 10px;
  height: 10px;
}

::-webkit-scrollbar-track {
  background: var(--amber-100);
}

::-webkit-scrollbar-thumb {
  background: var(--amber-600);
  border-radius: 5px;
}

::-webkit-scrollbar-thumb:hover {
  background: var(--amber-700);
}





// Museum Data
const museums = [
  {
    id: "geologi",
    name: "Museum Geologi Bandung",
    category: "Sains & Teknologi",
    description:
      "Museum Geologi Bandung adalah museum yang menyimpan dan mengelola koleksi geologi, seperti fosil, batuan, dan mineral. Didirikan pada 16 Mei 1928, museum ini memiliki koleksi fosil manusia purba dan replika kerangka dinosaurus.",
    image:
      "https://images.unsplash.com/photo-1686987195191-b3f91321d37d?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3Nzg4Nzd8MHwxfHNlYXJjaHwxfHxnZW9sb2d5JTIwbXVzZXVtJTIwaW5kb25lc2lhfGVufDF8fHx8MTc2NDU1ODQ5N3ww&ixlib=rb-4.1.0&q=80&w=1080",
    address: "Jl. Diponegoro No.57, Cihaur Geulis, Kec. Cibeunying Kaler, Kota Bandung",
    phone: "(022) 7213822",
    hours: "Senin-Kamis: 08:00-16:00, Sabtu-Minggu: 08:00-14:00",
    ticketPrice: "Rp 3.000 (Dewasa), Rp 2.000 (Anak-anak)",
    facilities: ["Parkir", "Toilet", "Musholla", "Perpustakaan", "Ruang Audio Visual"],
    website: "https://museum.geology.esdm.go.id",
    coordinates: { lat: -6.9004, lng: 107.6219 },
  },
  {
    id: "konferensi-asia-afrika",
    name: "Museum Konferensi Asia Afrika",
    category: "Sejarah",
    description:
      "Museum yang mengenang peristiwa bersejarah Konferensi Asia-Afrika tahun 1955. Gedung ini menyimpan berbagai dokumentasi, foto, dan benda-benda bersejarah dari konferensi yang menghasilkan Dasa Sila Bandung.",
    image:
      "https://images.unsplash.com/photo-1706264568861-81855ecf51a8?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3Nzg4Nzd8MHwxfHNlYXJjaHwxfHxhc2lhbiUyMGFmcmljYW4lMjBjb25mZXJlbmNlJTIwYnVpbGRpbmd8ZW58MXx8fHwxNzY0NTU4NDk4fDA&ixlib=rb-4.1.0&q=80&w=1080",
    address: "Jl. Asia Afrika No.65, Braga, Kec. Sumur Bandung, Kota Bandung",
    phone: "(022) 4233564",
    hours: "Selasa-Kamis: 08:00-16:00, Jumat: 14:00-16:00, Sabtu-Minggu: 09:00-16:00",
    ticketPrice: "Gratis",
    facilities: ["Parkir", "Toilet", "Perpustakaan", "Ruang Konferensi", "Gift Shop"],
    website: "https://mkaa.id",
    coordinates: { lat: -6.9215, lng: 107.6095 },
  },
  {
    id: "pos-indonesia",
    name: "Museum Pos Indonesia",
    category: "Sejarah & Komunikasi",
    description:
      "Museum yang menampilkan sejarah pos dan telekomunikasi Indonesia sejak zaman kolonial hingga modern. Koleksinya mencakup perangko langka, peralatan pos antik, dan teknologi komunikasi masa lalu.",
    image:
      "https://images.unsplash.com/photo-1730211939703-2e333d77d630?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3Nzg4Nzd8MHwxfHNlYXJjaHwxfHxwb3N0JTIwb2ZmaWNlJTIwbXVzZXVtfGVufDF8fHx8MTc2NDU1ODQ5OHww&ixlib=rb-4.1.0&q=80&w=1080",
    address: "Jl. Cilaki No.73, Citarum, Kec. Bandung Wetan, Kota Bandung",
    phone: "(022) 4207166",
    hours: "Selasa-Minggu: 09:00-15:00",
    ticketPrice: "Rp 2.000",
    facilities: ["Parkir", "Toilet", "Perpustakaan Filateli", "Ruang Edukasi"],
    coordinates: { lat: -6.9025, lng: 107.6307 },
  },
  {
    id: "sri-baduga",
    name: "Museum Sri Baduga",
    category: "Budaya & Tradisi",
    description:
      "Museum negeri yang menyimpan koleksi benda-benda budaya Jawa Barat, khususnya Sunda. Menampilkan berbagai artefak, keramik, wayang golek, dan benda-benda tradisional lainnya.",
    image:
      "https://images.unsplash.com/photo-1680144653445-9ea91934e5d1?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3Nzg4Nzd8MHwxfHNlYXJjaHwxfHx0cmFkaXRpb25hbCUyMGluZG9uZXNpYW4lMjBtdXNldW18ZW58MXx8fHwxNzY0NTU4NDk4fDA&ixlib=rb-4.1.0&q=80&w=1080",
    address: "Jl. BKR No.185, Pelindung Hewan, Kec. Astanaanyar, Kota Bandung",
    phone: "(022) 5200923",
    hours: "Selasa-Kamis: 08:00-15:00, Jumat: 08:00-11:00, Sabtu-Minggu: 08:00-14:00",
    ticketPrice: "Rp 5.000",
    facilities: ["Parkir", "Toilet", "Musholla", "Taman", "Ruang Pameran"],
    coordinates: { lat: -6.9447, lng: 107.5934 },
  },
  {
    id: "barli",
    name: "Museum Barli",
    category: "Seni & Budaya",
    description:
      "Museum seni rupa yang didedikasikan untuk karya-karya pelukis Barli Sasmitawinata. Menampilkan lebih dari 200 lukisan dengan berbagai tema, dari potret hingga pemandangan alam.",
    image:
      "https://images.unsplash.com/photo-1643820509303-79e98ac7e006?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3Nzg4Nzd8MHwxfHNlYXJjaHwxfHxhcnQlMjBnYWxsZXJ5JTIwbXVzZXVtfGVufDF8fHx8MTc2NDUyNzUyM3ww&ixlib=rb-4.1.0&q=80&w=1080",
    address: "Jl. Prof. Sutami No.91, Sukarasa, Kec. Sukasari, Kota Bandung",
    phone: "(022) 2013917",
    hours: "Senin-Sabtu: 09:00-15:00",
    ticketPrice: "Rp 10.000",
    facilities: ["Parkir", "Toilet", "Galeri", "Workshop Lukis"],
    coordinates: { lat: -6.8671, lng: 107.6033 },
  },
  {
    id: "mainan",
    name: "Museum Mainan",
    category: "Hiburan & Edukasi",
    description:
      "Museum yang menampilkan koleksi mainan dari berbagai negara dan era. Dari mainan tradisional Indonesia hingga action figures dan robot vintage dari Jepang.",
    image:
      "https://images.unsplash.com/photo-1764023488533-815876753b3e?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3Nzg4Nzd8MHwxfHNlYXJjaHwxfHx0b3klMjBtdXNldW0lMjB2aW50YWdlfGVufDF8fHx8MTc2NDU1ODQ5OXww&ixlib=rb-4.1.0&q=80&w=1080",
    address: "Jl. Setra Sari Kulon No.1, Sarijadi, Kec. Sukasari, Kota Bandung",
    phone: "(022) 2500748",
    hours: "Selasa-Minggu: 09:00-17:00",
    ticketPrice: "Rp 25.000 (Weekday), Rp 35.000 (Weekend)",
    facilities: ["Parkir", "Toilet", "Café", "Play Area", "Gift Shop"],
    coordinates: { lat: -6.8733, lng: 107.5888 },
  },
  {
    id: "mandala-wangsit",
    name: "Museum Mandala Wangsit Siliwangi",
    category: "Militer & Sejarah",
    description:
      "Museum yang menyimpan koleksi peralatan militer dan dokumentasi sejarah perjuangan TNI, khususnya Divisi Siliwangi. Menampilkan senjata, seragam, dan diorama perjuangan kemerdekaan.",
    image:
      "https://images.unsplash.com/photo-1745520387366-8ed7dde4c259?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3Nzg4Nzd8MHwxfHNlYXJjaHwxfHxtaWxpdGFyeSUyMG11c2V1bSUyMGJ1aWxkaW5nfGVufDF8fHx8MTc2NDU1ODQ5OXww&ixlib=rb-4.1.0&q=80&w=1080",
    address: "Jl. Lembong No.38, Braga, Kec. Sumur Bandung, Kota Bandung",
    phone: "(022) 4205346",
    hours: "Selasa-Minggu: 08:00-15:00",
    ticketPrice: "Gratis",
    facilities: ["Parkir", "Toilet", "Perpustakaan Militer", "Ruang Diorama"],
    coordinates: { lat: -6.9175, lng: 107.6098 },
  },
  {
    id: "gedung-sate",
    name: "Gedung Sate",
    category: "Sejarah & Arsitektur",
    description:
      "Ikon Kota Bandung yang dibangun tahun 1920 dengan arsitektur Indo-Eropa yang indah. Meski berfungsi sebagai kantor pemerintahan, gedung ini memiliki area museum yang terbuka untuk umum.",
    image:
      "https://images.unsplash.com/photo-1631650669141-ee124e2f641f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3Nzg4Nzd8MHwxfHNlYXJjaHwxfHxiYW5kdW5nJTIwY2l0eSUyMGhlcml0YWdlfGVufDF8fHx8MTc2NDU1ODQ5OXww&ixlib=rb-4.1.0&q=80&w=1080",
    address: "Jl. Diponegoro No.22, Citarum, Kec. Bandung Wetan, Kota Bandung",
    phone: "(022) 4264440",
    hours: "Senin-Jumat: 08:00-16:00 (dengan pemberitahuan sebelumnya)",
    ticketPrice: "Gratis",
    facilities: ["Parkir", "Toilet", "Taman", "Area Foto"],
    coordinates: { lat: -6.9024, lng: 107.6186 },
  },
];

// State
let currentFilter = "Semua";
let searchQuery = "";
let filteredMuseums = [...museums];

// DOM Elements
const menuToggle = document.getElementById("menuToggle");
const mobileNav = document.getElementById("mobileNav");
const heroSearch = document.getElementById("heroSearch");
const museumSearch = document.getElementById("museumSearch");
const filterButtons = document.getElementById("filterButtons");
const museumGrid = document.getElementById("museumGrid");
const museumModal = document.getElementById("museumModal");
const closeModal = document.getElementById("closeModal");

// Initialize
function init() {
  createFilterButtons();
  renderMuseums();
  setupEventListeners();
}

// Mobile Menu Toggle
function setupEventListeners() {
  menuToggle.addEventListener("click", () => {
    mobileNav.classList.toggle("active");
  });

  // Search functionality
  heroSearch.addEventListener("input", (e) => {
    searchQuery = e.target.value.toLowerCase();
    filterMuseums();

    if (searchQuery) {
      document.getElementById("museums").scrollIntoView({ behavior: "smooth" });
    }
  });

  museumSearch.addEventListener("input", (e) => {
    searchQuery = e.target.value.toLowerCase();
    filterMuseums();
  });

  // Close modal
  closeModal.addEventListener("click", () => {
    museumModal.classList.remove("active");
    document.body.style.overflow = "auto";
  });

  museumModal.addEventListener("click", (e) => {
    if (e.target === museumModal) {
      museumModal.classList.remove("active");
      document.body.style.overflow = "auto";
    }
  });
}

// Create Filter Buttons
function createFilterButtons() {
  const categories = ["Semua", ...new Set(museums.map((m) => m.category))];

  categories.forEach((category) => {
    const button = document.createElement("button");
    button.className = `filter-btn ${category === currentFilter ? "active" : ""}`;
    button.textContent = category;

    button.addEventListener("click", () => {
      currentFilter = category;
      updateFilterButtons();
      filterMuseums();
    });

    filterButtons.appendChild(button);
  });
}

// Update Filter Buttons
function updateFilterButtons() {
  const buttons = filterButtons.querySelectorAll(".filter-btn");

  buttons.forEach((button) => {
    button.classList.toggle("active", button.textContent === currentFilter);
  });
}

// Filter Museums
function filterMuseums() {
  filteredMuseums = museums.filter((museum) => {
    const matchesSearch =
      museum.name.toLowerCase().includes(searchQuery) ||
      museum.description.toLowerCase().includes(searchQuery) ||
      museum.category.toLowerCase().includes(searchQuery);

    const matchesCategory =
      currentFilter === "Semua" || museum.category === currentFilter;

    return matchesSearch && matchesCategory;
  });

  renderMuseums();
}

// Render Museums
function renderMuseums() {
  museumGrid.innerHTML = "";

  if (filteredMuseums.length === 0) {
    museumGrid.innerHTML =
      '<div style="text-align: center; padding: 3rem; color: var(--amber-600); grid-column: 1 / -1;">Tidak ada museum yang ditemukan</div>';
    return;
  }

  filteredMuseums.forEach((museum, index) => {
    museumGrid.appendChild(createMuseumCard(museum, index));
  });
}

// Create Museum Card
function createMuseumCard(museum, index) {
  const card = document.createElement("div");
  card.className = "museum-card";
  card.style.animation = `fadeIn 0.5s ease ${index * 0.1}s both`;

  card.innerHTML = `
    <div class="museum-card-image">
      <img src="${museum.image}" alt="${museum.name}" loading="lazy">
      <div class="museum-category">${museum.category}</div>
    </div>

    <div class="museum-card-content">
      <h3>${museum.name}</h3>
      <p class="museum-description">${museum.description}</p>

      <div class="museum-info">
        <div class="info-row">
          <svg width="16" height="16" stroke-width="2">
            <path d="M20 10c0 6-8 12-8 12s-8-6-8-12a8 8 0 0 1 16 0Z"></path>
            <circle cx="12" cy="10" r="3"></circle>
          </svg>
          <span class="info-text">${museum.address}</span>
        </div>

        <div class="info-row">
          <svg width="16" height="16" stroke-width="2">
            <circle cx="12" cy="12" r="10"></circle>
            <polyline points="12 6 12 12 16 14"></polyline>
          </svg>
          <span class="info-text">${museum.hours.split(",")[0]}</span>
        </div>

        <div class="info-row">
          <svg width="16" height="16" stroke-width="2">
            <path d="M2 9a3 3 0 0 1 0 6v2a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2v-2a3 3 0 0 1 0-6V7a2 2 0 0 0-2-2H4a2 2 0 0 0-2 2Z"></path>
            <path d="M13 5v2"></path>
            <path d="M13 17v2"></path>
            <path d="M13 11v2"></path>
          </svg>
          <span class="info-text">${museum.ticketPrice.split(",")[0]}</span>
        </div>
      </div>

      <button class="museum-card-button">Lihat Detail</button>
    </div>
  `;

  card.addEventListener("click", () => openMuseumDetail(museum));

  return card;
}

// Open Museum Detail Modal
function openMuseumDetail(museum) {
  document.getElementById("modalImage").src = museum.image;
  document.getElementById("modalImage").alt = museum.name;
  document.getElementById("modalCategory").textContent = museum.category;
  document.getElementById("modalName").textContent = museum.name;
  document.getElementById("modalAddress").textContent = museum.address;
  document.getElementById("modalDescription").textContent = museum.description;
  document.getElementById("modalHours").textContent = museum.hours;
  document.getElementById("modalPrice").textContent = museum.ticketPrice;
  document.getElementById("modalPhone").textContent = museum.phone;
  document.getElementById(
    "modalCoordinates"
  ).textContent = `${museum.coordinates.lat}, ${museum.coordinates.lng}`;

  const facilitiesGrid = document.getElementById("modalFacilities");
  facilitiesGrid.innerHTML = "";

  museum.facilities.forEach((facility) => {
    const div = document.createElement("div");
    div.className = "facility-item";

    div.innerHTML = `
      <div class="facility-icon">
        <svg width="16" height="16" stroke-width="2">
          <polyline points="20 6 9 17 4 12"></polyline>
        </svg>
      </div>
      <span class="facility-name">${facility}</span>
    `;

    facilitiesGrid.appendChild(div);
  });

  const websiteButton = document.getElementById("websiteButton");

  websiteButton.innerHTML = museum.website
    ? `<a href="${museum.website}" target="_blank" rel="noopener noreferrer" class="btn-primary btn-full" style="display: block; text-align: center; text-decoration: none; margin-bottom: 1rem;">
        Kunjungi Website
      </a>`
    : "";

  museumModal.classList.add("active");
  document.body.style.overflow = "hidden";
  museumModal.scrollTop = 0;
}

// Fade animation
const style = document.createElement("style");
style.textContent = `
  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }
`;
document.head.appendChild(style);

// Init
if (document.readyState === "loading") {
  document.addEventListener("DOMContentLoaded", init);
} else {
  init();
}
