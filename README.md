<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AxiomLearn - Master AI Prompt Engineering</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', system-ui, sans-serif; }
        body { background: #0F172A; color: white; line-height: 1.6; }
        .container { max-width: 1200px; margin: 0 auto; padding: 0 20px; }
        
        /* Header */
        header { padding: 2rem 0; border-bottom: 1px solid #1E293B; }
        .logo { font-size: 1.8rem; font-weight: 800; color: #3B82F6; }
        
        /* Hero */
        .hero { text-align: center; padding: 5rem 0; }
        .hero h1 { font-size: 3.5rem; margin-bottom: 1rem; background: linear-gradient(90deg, #3B82F6, #8B5CF6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .hero p { font-size: 1.3rem; color: #94A3B8; max-width: 700px; margin: 0 auto 2rem; }
        .cta-button { background: #3B82F6; color: white; padding: 1rem 2.5rem; border-radius: 50px; font-size: 1.1rem; font-weight: 600; border: none; cursor: pointer; text-decoration: none; display: inline-block; }
        .cta-button:hover { background: #2563EB; }
        
        /* Features */
        .features { padding: 5rem 0; }
        .section-title { text-align: center; font-size: 2.5rem; margin-bottom: 3rem; }
        .features-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; }
        .feature-card { background: #1E293B; padding: 2rem; border-radius: 15px; border: 1px solid #334155; }
        .feature-icon { font-size: 2.5rem; margin-bottom: 1rem; }
        .feature-card h3 { font-size: 1.5rem; margin-bottom: 1rem; color: #3B82F6; }
        
        /* Pricing */
        .pricing { padding: 5rem 0; background: #1E293B; }
        .pricing-cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 2rem; margin-top: 3rem; }
        .pricing-card { background: #0F172A; padding: 2.5rem; border-radius: 15px; border: 2px solid #334155; }
        .pricing-card.featured { border-color: #3B82F6; transform: scale(1.05); }
        .price { font-size: 3rem; font-weight: 800; color: #3B82F6; }
        .pricing-card ul { list-style: none; margin: 2rem 0; }
        .pricing-card li { padding: 0.5rem 0; border-bottom: 1px solid #334155; }
        
        /* Footer */
        footer { padding: 3rem 0; text-align: center; border-top: 1px solid #1E293B; color: #64748B; }
        
        @media (max-width: 768px) {
            .hero h1 { font-size: 2.5rem; }
            .pricing-card.featured { transform: none; }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">AxiomLearn</div>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h1>Master AI Prompt Engineering for Business</h1>
            <p>The 4-Week Sprint Where You Build & Deploy a Custom AI System for Your Actual Job</p>
            <a href="#pricing" class="cta-button">Join 2026 Cohort - $197 Pre-Sell</a>
        </div>
    </section>

    <section class="features">
        <div class="container">
            <h2 class="section-title">Powered by Our AI Mentor System</h2>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">🧠</div>
                    <h3>DepthForge AI</h3>
                    <p>Generates personalized business challenges based on your role and industry.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">⚡</div>
                    <h3>Human-Link Guarantee</h3>
                    <p>Book 30-minute expert calls within 24 hours. No ticket queues.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">🛡️</div>
                    <h3>TrustGuard AI</h3>
                    <p>Automatic refunds within 14 days. No hidden subscriptions.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="pricing" class="pricing">
        <div class="container">
            <h2 class="section-title">Choose Your Transformation</h2>
            <div class="pricing-cards">
                <div class="pricing-card">
                    <h3>Founder Access</h3>
                    <div class="price">$197</div>
                    <ul>
                        <li>Lifetime course access</li>
                        <li>3 Custom AI projects</li>
                        <li>2 Expert strategy calls</li>
                        <li>Private community</li>
                        <li>2026 cohort priority</li>
                    </ul>
                    <a href="#" class="cta-button">Get Founder Pricing</a>
                </div>
                <div class="pricing-card featured">
                    <h3>Standard Enrollment</h3>
                    <div class="price">$497</div>
                    <ul>
                        <li>Lifetime course access</li>
                        <li>3 Custom AI projects</li>
                        <li>1 Expert review call</li>
                        <li>Verified certification</li>
                        <li>All course materials</li>
                    </ul>
                    <a href="#" class="cta-button">Join Waitlist</a>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>© 2025 AxiomLearn. All rights reserved.</p>
            <p>Contact: hello@axiomlearn.com</p>
        </div>
    </footer>
</body>
</html>
