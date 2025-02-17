<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OSINT Framework</title>
    <style>
  body {
    display: flex;
    flex-direction: column;
    align-items: center;
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: lightskyblue;
}

header, footer {
    width: 100%;
    text-align: center;
    padding: 20px;
    background-color: #007BFF;
    color: black;
    font-family: 'Times New Roman', Times, serif;
}

header h1, footer h2 {
    margin: 0;
    font-size: 2em;
}

main {
    width: 100%;
    max-width: 1200px; /* Laptop-க்கு proper width */
    display: flex;
    flex-direction: column;
    align-items: center;
}

.card {
    display: flex;
    flex-direction: row; /* Default desktop-க்கு row-wise */
    align-items: center;
    background-color: rgb(5, 90, 90);
    padding: 20px;
    width: 90%;
    max-width: 1000px;
    border: 1px solid #ddd;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    margin: 20px 0;
    text-align: center;
}

.card img {
    height: 250px;
    margin-left: 20px;
    max-width: 100%;
    border-radius: 8px;
}

.card .text {
    flex: 1;
    text-align: left;
    color: white;
}

.card h2 a {
    text-decoration: none;
    color: #007BFF;
    text-align: center;
}

.card ul {
    padding-left: 20px;
}

.card p {
    font-style: italic;
}

/* ✅ Mobile View Fix */
@media (max-width: 768px) {
    .card {
        flex-direction: column; /* Mobile-ல column-wise */
        text-align: center;
    }
    .card img {
        margin: 10px 0;
        width: 100%; /* Mobile-ல image full width */
        height: auto;
    }
    .card .text {
        text-align: center;
    }
}
    </style>
</head>
<body>
    <header>
        <h1>OSINT Framework</h1>
        <p>Explore tools for Open Source Intelligence</p>
    </header>

    <main>
        <!-- Card 1 -->
        <div class="card">
            <div class="text">
                <h2 align="center"><a href="https://nslookup.io" target="_blank">IP Address</a></h2>
                <p>A record (Address Record) points a domain or subdomain to an IP address. 
                    For example, an A Record is used to point a logical domain name, such as "google.com," to the IP address of Google's
                     hosting server, "74.125.224.147".</p>
                <ul>
                    <li>CNAME Record</li>
                    <li>MX Record</li>
                    <li>TXT Record</li>
                    <li>SRV Record</li>
                    <li>AAAA Record</li>
                </ul>
            </div>
            <img src="https://ruurtjan.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fdns-lookup.5814af55.png&w=3840&q=75" alt="IP Address Illustration">
        </div>

        <!-- Card 2 -->
        <div class="card">
            <div class="text">
                <h2 align="center"><a href="https://www.whois.com/whois/" target="_blank">Domain Register Record Information</a></h2>
                <p>A Whois domain lookup allows you to trace the ownership and tenure of a domain name. 
                    imilar to how all houses are registered with a governing authority, all domain name registries maintain a record of 
                    information about every domain name purchased through them, along with who owns it, and the date till which it has 
                    been purchased.</p>
                <ul>
                    <li>Investigating domain history</li>
                    <li>Verifying domain ownership</li>
                    <li>Checking domain availability</li>
                </ul>
            </div>
            <img src="https://jamesnames.com/wp-content/uploads/2021/06/Screen-Shot-2021-06-03-at-13.44.16.png" alt="Whois Lookup Tool">
        </div>

        <!-- Card 3 -->
        <div class="card">
            <div class="text">
                <h2 align="center"><a href="https://haveibeenpwned.com/" target="_blank">Email Address in Data Breach</a></h2>
                <p>Have I Been Pwned? is a website that allows Internet users to check whether their personal data has 
                    been compromised by data breaches. The site has been widely touted as a valuable resource for Internet users wishing
                     to protect their own security and privacy.</p>
                <ul>
                    <li>Protect personal information</li>
                    <li>Encourage password updates</li>
                    <li>Investigate breaches</li>
                </ul>
            </div>
            <img src="https://i.dailymail.co.uk/i/pix/2017/08/07/11/430B10E400000578-0-image-a-32_1502101523740.jpg" alt="Data Breach Illustration">
        </div>

        <!-- Card 4 -->
        <div class="card">
            <div class="text">
                <h2 align="center"><a href="https://wheregoes.com/" target="_blank">URL Redirect Checker</a></h2>
                <p>Where does this link go? The URL redirect checker follows the path of the URL. It will show you the 
                    full redirection path of URLs, shortened links, or tiny URLs. Also referred to as a link checker, url checker, 
                    redirect checker, link tracker, url tracker, redirect tracer, link follower, 301 redirect checker, redirect tracker, 
                    URL tester, and so on.</p>
                <ul>
                    <li>Identify network issues</li>
                    <li>Troubleshoot performance</li>
                    <li>Optimize paths</li>
                </ul>
            </div>
            <img src="https://preview.atlaq.com/fe6992e5ec47e4acdac3596b81339dec_wheregoes.com.png" alt="Redirect Checker Illustration">
        </div>

        <!-- Card 5 -->
        <div class="card">
            <div class="text">
                <h2 align="center"><a href="https://www.virustotal.com/gui/home/upload" target="_blank">Malware Analysis</a></h2>
                <p>Analyse suspicious files, domains, IPs and URLs to detect malware and other breaches, automatically 
                    share them with the security community. </p>
                <ul>
                    <li>Check files and URLs before opening</li>
                    <li>Detect and analyze malware</li>
                    <li>Assist in digital forensics</li>
                </ul>
            </div>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRJGre-guJVmHN1wzxroKQwR8W0YXsPZ3KMwg&s" alt="Malware Analysis Illustration">
        </div>

        <!-- Card 6 -->
        <div class="card">
            <div class="text">
                <h2 align="center"><a href="https://tineye.com/" target="_blank">Reverse Image Search</a></h2>
                <p>TinEye is a reverse image search engine developed and offered by Idée, Inc., a company based in Toronto, Ontario,
                    Canada. It is the first image search engine on the web to use image identification technology rather than keywords, 
                    metadata or watermarks.</p>
                <ul>
                    <li>Find higher-quality images</li>
                    <li>Identify unauthorized use</li>
                    <li>Assist in copyright investigations</li>
                </ul>
            </div>
            <img src="https://www.zdnet.com/a/img/resize/ac1826854692901fe788f26638f8074f39808639/2016/07/31/f436de30-3f53-4f2c-8c4b-99fc5a9888f4/ziff-tineye.jpg?auto=webp&width=1280" alt="Reverse Image Search Illustration">
        </div>
    </main>

    <footer>
        <hr>
        <p><i>By</i></p>
        <p><i>Nitharshana N</i></p>
        <p><i>Tharani C</i></p>
        <p><i>Lithika V</i></p>
        <h2>&copy; <i>Copyright</i></h2>
    </footer>
</body>
</html>   
