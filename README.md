<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Master AI Prompt Engineering for Business | 4-Week Sprint</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; }
        body { background: #0F172A; color: #FFFFFF; line-height: 1.6; }
        .container { max-width: 1200px; margin: 0 auto; padding: 0 20px; }
        
        /* Header */
        header { padding: 1.5rem 0; border-bottom: 1px solid #1E293B; }
        .logo { font-size: 1.8rem; font-weight: 800; color: #3B82F6; text-decoration: none; }
        
        /* Hero */
        .hero { text-align: center; padding: 5rem 0; background: linear-gradient(135deg, #0F172A 0%, #1E293B 100%); }
        .hero h1 { font-size: 3rem; margin-bottom: 1.5rem; background: linear-gradient(90deg, #3B82F6, #8B5CF6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .hero p { font-size: 1.2rem; color: #94A3B8; max-width: 700px; margin: 0 auto 2.5rem; }
        .btn-primary { background: #3B82F6; color: white; padding: 1rem 2.5rem; border-radius: 8px; font-size: 1.1rem; font-weight: 600; border: none; cursor: pointer; text-decoration: none; display: inline-block; transition: all 0.3s; }
        .btn-primary:hover { background: #2563EB; transform: translateY(-2px); box-shadow: 0 10px 25px rgba(37, 99, 235, 0.3); }
        .btn-secondary { color: #3B82F6; text-decoration: none; font-weight: 500; display: block; margin-top: 1.5rem; }
        
        /* Sections */
        section { padding: 5rem 0; }
        .section-title { text-align: center; font-size: 2.5rem; margin-bottom: 3rem; color: #F1F5F9; }
        
        /* Problem Cards */
        .problem-cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; margin-top: 2rem; }
        .problem-card { background: #1E293B; padding: 2rem; border-radius: 12px; border: 1px solid #334155; text-align: center; }
        .problem-card h3 { color: #F87171; font-size: 1.3rem; margin-bottom: 1rem; }
        
        /* Timeline */
        .timeline { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 2rem; margin-top: 3rem; }
        .timeline-item { text-align: center; padding: 2rem; background: #1E293B; border-radius: 12px; }
        .timeline-number { background: #3B82F6; color: white; width: 50px; height: 50px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 1.5rem; font-weight: 800; margin: 0 auto 1rem; }
        
        /* Features */
        .features-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; margin-top: 3rem; }
        .feature-card { background: #1E293B; padding: 2rem; border-radius: 12px; border: 1px solid #334155; }
        .feature-icon { font-size: 2.5rem; margin-bottom: 1rem; }
        .feature-card h3 { color: #3B82F6; font-size: 1.5rem; margin-bottom: 1rem; }
        
        /* Pricing */
        .pricing-cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; margin-top: 3rem; }
        .pricing-card { background: #1E293B; padding: 2.5rem; border-radius: 15px; border: 2px solid #334155; }
        .pricing-card.featured { border-color: #3B82F6; transform: scale(1.05); }
        .price { font-size: 3rem; font-weight: 800; color: #3B82F6; margin: 1rem 0; }
        .pricing-card ul { list-style: none; margin: 2rem 0; }
        .pricing-card li { padding: 0.8rem 0; border-bottom: 1px solid #334155; display: flex; align-items: center; }
        .pricing-card li:before { content: "✓"; color: #10B981; margin-right: 10px; }
        
        /* Checklist */
        .checklist { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1rem; margin-top: 2rem; }
        .checklist-item { display: flex; align-items: center; padding: 1rem; background: #1E293B; border-radius: 8px; }
        
        /* Comparison */
        .comparison { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; margin-top: 2rem; }
        .comparison-col { padding: 2rem; border-radius: 12px; }
        .comparison-col.good { background: rgba(16, 185, 129, 0.1); border: 1px solid #10B981; }
        .comparison-col.bad { background: rgba(239, 68, 68, 0.1); border: 1px solid #EF4444; }
        
        /* FAQ */
        .faq-item { background: #1E293B; padding: 1.5rem; border-radius: 10px; margin-bottom: 1rem; }
        .faq-question { color: #3B82F6; font-weight: 600; margin-bottom: 0.5rem; }
        
        /* Footer */
        footer { padding: 3rem 0; text-align: center; border-top: 1px solid #1E293B; color: #64748B; }
        
        /* Responsive */
        @media (max-width: 768px) {
            .hero h1 { font-size: 2.2rem; }
            .section-title { font-size: 2rem; }
            .pricing-card.featured { transform: none; }
            .pricing-cards, .features-grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <a href="#" class="logo">AxiomLearn</a>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h1>Master AI Prompt Engineering for Business</h1>
            <p>The 4-Week Sprint Where You Build & Deploy a Custom AI System for Your Actual Job</p>
            <a href="YOUR_GUMROAD_LINK_HERE" class="btn-primary">Join 2026 Cohort - $197 Pre-Sell</a>
            <a href="#" class="btn-secondary">Download Course Syllabus (PDF)</a>
        </div>
    </section>

    <section>
        <div class="container">
            <h2 class="section-title">Why AI Courses Disappoint Professionals</h2>
            <div class="problem-cards">
                <div class="problem-card">
                    <h3>Shallow Theory</h3>
                    <p>Watch videos but never apply to your real work</p>
                </div>
                <div class="problem-card">
                    <h3>No Real Support</h3>
                    <p>Get stuck with AI chatbots instead of human experts</p>
                </div>
                <div class="problem-card">
                    <h3>Hidden Traps</h3>
                    <p>Surprise subscriptions and denied refunds</p>
                </div>
            </div>
        </div>
    </section>

    <section>
        <div class="container">
            <h2 class="section-title">Learn by Building: Your 4-Week Transformation</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-number">1</div>
                    <h3>Week 1: Foundation</h3>
                    <p>Your Custom AI Challenge</p>
                </div>
                <div class="timeline-item">
                    <div class="timeline-number">2</div>
                    <h3>Week 2: Advanced</h3>
                    <p>Personalized Feedback</p>
                </div>
                <div class="timeline-item">
                    <div class="timeline-number">3</div>
                    <h3>Week 3: Automation</h3>
                    <p>Working System Design</p>
                </div>
                <div class="timeline-item">
                    <div class="timeline-number">4</div>
                    <h3>Week 4: Deployment</h3>
                    <p>Portfolio-Ready Project</p>
                </div>
            </div>
            <p style="text-align: center; margin-top: 2rem; color: #94A3B8;">"Each week, you build part of your actual AI workflow"</p>
        </div>
    </section>

    <section>
        <div class="container">
            <h2 class="section-title">Powered by Our AI Mentor System</h2>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">🧠</div>
                    <h3>DepthForge AI</h3>
                    <p>Generates personalized business challenges based on your specific role and industry. No generic exercises.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">⚡</div>
                    <h3>Human-Link Guarantee</h3>
                    <p>Stuck? Book a 30-minute video call with an expert within 24 hours. No ticket queues.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">🛡️</div>
                    <h3>TrustGuard AI</h3>
                    <p>Automatic refunds within 14 days. No hidden subscriptions. One-time payment only.</p>
                </div>
            </div>
        </div>
    </section>

    <section>
        <div class="container">
            <h2 class="section-title">Choose Your Transformation Path</h2>
            <div class="pricing-cards">
                <div class="pricing-card">
                    <h3>Pre-Sell Founder's Access</h3>
                    <div class="price">$197</div>
                    <ul>
                        <li>Lifetime course access</li>
                        <li>3 AI-generated custom projects</li>
                        <li>2× 30-minute founder strategy calls</li>
                        <li>Private community access</li>
                        <li>Early 2026 enrollment</li>
                    </ul>
                    <a href="YOUR_GUMROAD_LINK_HERE" class="btn-primary">Get Founder Pricing</a>
                </div>
                <div class="pricing-card featured">
                    <h3>Standard Enrollment</h3>
                    <div class="price">$497</div>
                    <ul>
                        <li>Lifetime course access</li>
                        <li>3 AI-generated custom projects</li>
                        <li>1× expert review call</li>
                        <li>Private community</li>
                        <li>Official certification</li>
                    </ul>
                    <a href="#" class="btn-primary">Waitlist for Standard</a>
                </div>
                <div class="pricing-card">
                    <h3>Team License</h3>
                    <div class="price">$997</div>
                    <ul>
                        <li>3 team member licenses</li>
                        <li>Team dashboard</li>
                        <li>Group coaching session</li>
                        <li>Custom industry challenges</li>
                    </ul>
                    <a href="#" class="btn-primary">Contact for Teams</a>
                </div>
            </div>
            <p style="text-align: center; margin-top: 2rem; color: #94A3B8; font-size: 0.9rem;">14-Day Zero-Risk Guarantee: Complete Week 1, if not satisfied, get full refund.</p>
        </div>
    </section>

    <section>
        <div class="container">
            <h2 class="section-title">Everything Included in Your Journey</h2>
            <div class="checklist">
                <div class="checklist-item">12 Video Lessons (5-15 min each)</div>
                <div class="checklist-item">3 Custom AI-Generated Business Challenges</div>
                <div class="checklist-item">1 Portfolio-Ready Project</div>
                <div class="checklist-item">4 Weekly Progress Reviews</div>
                <div class="checklist-item">30-Minute Expert Strategy Call</div>
                <div class="checklist-item">Private Community Access</div>
                <div class="checklist-item">Verified Skill Certificate</div>
                <div class="checklist-item">Prompt Library Templates ($500 Value)</div>
                <div class="checklist-item">Lifetime Updates & Access</div>
            </div>
        </div>
    </section>

    <section>
        <div class="container">
            <h2 class="section-title">Designed for Real Professionals</h2>
            <div class="comparison">
                <div class="comparison-col good">
                    <h3 style="color: #10B981;">✅ PERFECT FOR</h3>
                    <p>Marketing managers</p>
                    <p>Founders & Executives</p>
                    <p>Consultants</p>
                    <p>Team leaders implementing AI</p>
                </div>
                <div class="comparison-col bad">
                    <h3 style="color: #EF4444;">❌ NOT FOR</h3>
                    <p>"Get rich quick" seekers</p>
                    <p>Unwilling to practice 4-6 hours/week</p>
                    <p>Complete AI beginners</p>
                </div>
            </div>
        </div>
    </section>

    <section>
        <div class="container">
            <h2 class="section-title">2026 Cohort Timeline</h2>
            <div style="background: #1E293B; padding: 2rem; border-radius: 12px; margin-top: 2rem;">
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1rem; text-align: center;">
                    <div>
                        <h3 style="color: #3B82F6;">Pre-Sell</h3>
                        <p>Now - Jan 31, 2025</p>
                        <p style="color: #3B82F6; font-weight: 600;">$197 price</p>
                    </div>
                    <div>
                        <h3 style="color: #3B82F6;">Cohort 1 Launch</h3>
                        <p>February 3, 2026</p>
                        <p>Limited to 100 students</p>
                    </div>
                    <div>
                        <h3 style="color: #3B82F6;">Next Cohort</h3>
                        <p>April 2026</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section>
        <div class="container">
            <h2 class="section-title">Frequently Asked Questions</h2>
            <div class="faq-item">
                <div class="faq-question">"When do I get access?"</div>
                <p>Pre-sell buyers get immediate syllabus + strategy call booking. Full course access begins February 2026.</p>
            </div>
            <div class="faq-item">
                <div class="faq-question">"What if I need help?"</div>
                <p>Human-Link Guarantee: Book a 30-minute expert call within 24 hours. Plus community support.</p>
            </div>
            <div class="faq-item">
                <div class="faq-question">"What's required?"</div>
                <p>Computer, internet, 4-6 hours/week, ChatGPT Plus account (we help set up).</p>
            </div>
            <div class="faq-item">
                <div class="faq-question">"Refund policy?"</div>
                <p>14-Day Zero-Risk: Complete Week 1, if not satisfied, email for full refund. No questions.</p>
            </div>
        </div>
    </section>

    <section class="hero">
        <div class="container">
            <h2>Build Your AI Advantage Before Your Competitors Do</h2>
            <p>"Join 100 professionals transforming their work with AI"</p>
            <a href="YOUR_GUMROAD_LINK_HERE" class="btn-primary">Secure My Founder's Access - $197</a>
            <p style="margin-top: 1rem; font-size: 0.9rem; color: #94A3B8;">First 10 buyers get: 1) Price locked forever, 2) Monthly Q&A for 6 months</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p style="font-size: 1.2rem; color: #3B82F6; margin-bottom: 1rem;">AxiomLearn</p>
            <p style="margin-bottom: 1rem;">
                <a href="#" style="color: #94A3B8; margin: 0 10px;">Contact</a> • 
                <a href="#" style="color: #94A3B8; margin: 0 10px;">Privacy Policy</a> • 
                <a href="#" style="color: #94A3B8; margin: 0 10px;">Terms</a>
            </p>
            <p>hello@masteraiprompt.com</p>
            <p style="margin-top: 2rem; font-size: 0.9rem;">© 2025 AxiomLearn. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>.   <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Master AI Prompt Engineering for Business | 4-Week Sprint</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; }
        body { background: #0A0F24; color: #FFFFFF; line-height: 1.6; }
        .container { max-width: 1200px; margin: 0 auto; padding: 0 20px; }
        
        /* Header */
        header { padding: 1.5rem 0; background: rgba(10, 15, 36, 0.95); backdrop-filter: blur(10px); position: sticky; top: 0; z-index: 100; }
        .logo { font-size: 1.8rem; font-weight: 800; background: linear-gradient(90deg, #00D4FF, #6C63FF); -webkit-background-clip: text; -webkit-text-fill-color: transparent; text-decoration: none; }
        
        /* Hero */
        .hero { text-align: center; padding: 6rem 0; background: radial-gradient(circle at top right, #1A1F3A 0%, #0A0F24 70%); position: relative; overflow: hidden; }
        .hero::before { content: ''; position: absolute; top: -50%; left: -50%; width: 200%; height: 200%; background: radial-gradient(circle, rgba(0, 212, 255, 0.1) 0%, transparent 70%); }
        .hero h1 { font-size: 3.2rem; margin-bottom: 1.5rem; background: linear-gradient(90deg, #00D4FF, #6C63FF); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .hero p { font-size: 1.3rem; color: #B0B7D6; max-width: 700px; margin: 0 auto 3rem; }
        .btn-primary { background: linear-gradient(90deg, #00D4FF, #6C63FF); color: white; padding: 1.2rem 3rem; border-radius: 12px; font-size: 1.1rem; font-weight: 600; border: none; cursor: pointer; text-decoration: none; display: inline-block; transition: all 0.3s; box-shadow: 0 10px 30px rgba(0, 212, 255, 0.3); }
        .btn-primary:hover { transform: translateY(-3px); box-shadow: 0 15px 40px rgba(0, 212, 255, 0.4); }
        .btn-secondary { color: #00D4FF; text-decoration: none; font-weight: 500; display: block; margin-top: 2rem; font-size: 1.1rem; }
        
        /* Sections */
        section { padding: 5rem 0; }
        .section-title { text-align: center; font-size: 2.8rem; margin-bottom: 3rem; color: #FFFFFF; position: relative; }
        .section-title::after { content: ''; display: block; width: 80px; height: 4px; background: linear-gradient(90deg, #00D4FF, #6C63FF); margin: 1rem auto; border-radius: 2px; }
        
        /* Problem Cards */
        .problem-cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; margin-top: 2rem; }
        .problem-card { background: rgba(26, 31, 58, 0.8); padding: 2.5rem; border-radius: 16px; border: 1px solid rgba(0, 212, 255, 0.2); text-align: center; transition: all 0.3s; backdrop-filter: blur(10px); }
        .problem-card:hover { transform: translateY(-5px); border-color: #00D4FF; box-shadow: 0 15px 40px rgba(0, 212, 255, 0.2); }
        .problem-card h3 { color: #FF6B8B; font-size: 1.4rem; margin-bottom: 1rem; }
        
        /* Timeline */
        .timeline { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 2rem; margin-top: 3rem; }
        .timeline-item { text-align: center; padding: 2.5rem; background: rgba(26, 31, 58, 0.8); border-radius: 16px; border: 1px solid rgba(108, 99, 255, 0.2); position: relative; }
        .timeline-number { background: linear-gradient(135deg, #00D4FF, #6C63FF); color: white; width: 60px; height: 60px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 1.8rem; font-weight: 800; margin: 0 auto 1.5rem; box-shadow: 0 10px 20px rgba(0, 212, 255, 0.3); }
        
        /* Features */
        .features-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; margin-top: 3rem; }
        .feature-card { background: rgba(26, 31, 58, 0.8); padding: 2.5rem; border-radius: 16px; border: 1px solid rgba(0, 212, 255, 0.2); transition: all 0.3s; backdrop-filter: blur(10px); }
        .feature-card:hover { transform: translateY(-5px); border-color: #6C63FF; }
        .feature-icon { font-size: 3rem; margin-bottom: 1.5rem; }
        .feature-card h3 { color: #00D4FF; font-size: 1.6rem; margin-bottom: 1rem; }
        .feature-card p { color: #B0B7D6; }
        
        /* Pricing */
        .pricing-cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2.5rem; margin-top: 3rem; }
        .pricing-card { background: rgba(26, 31, 58, 0.9); padding: 3rem; border-radius: 20px; border: 2px solid rgba(108, 99, 255, 0.3); position: relative; overflow: hidden; }
        .pricing-card::before { content: ''; position: absolute; top: 0; left: 0; right: 0; height: 5px; background: linear-gradient(90deg, #00D4FF, #6C63FF); }
        .pricing-card.featured { border-color: #00D4FF; transform: scale(1.05); box-shadow: 0 20px 50px rgba(0, 212, 255, 0.2); }
        .price { font-size: 3.5rem; font-weight: 800; background: linear-gradient(90deg, #00D4FF, #6C63FF); -webkit-background-clip: text; -webkit-text-fill-color: transparent; margin: 1.5rem 0; }
        .pricing-card ul { list-style: none; margin: 2.5rem 0; }
        .pricing-card li { padding: 1rem 0; border-bottom: 1px solid rgba(255, 255, 255, 0.1); display: flex; align-items: center; color: #E2E8F0; }
        .pricing-card li:before { content: "✓"; color: #00FF9D; margin-right: 15px; font-weight: bold; font-size: 1.2rem; }
        
        /* Checklist */
        .checklist { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1.5rem; margin-top: 2rem; }
        .checklist-item { display: flex; align-items: center; padding: 1.5rem; background: rgba(26, 31, 58, 0.6); border-radius: 12px; border-left: 4px solid #00D4FF; color: #E2E8F0; }
        .checklist-item:before { content: "▶"; color: #00D4FF; margin-right: 15px; font-weight: bold; }
        
        /* Comparison */
        .comparison { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2.5rem; margin-top: 2rem; }
        .comparison-col { padding: 2.5rem; border-radius: 16px; }
        .comparison-col.good { background: rgba(0, 255, 157, 0.1); border: 1px solid #00FF9D; }
        .comparison-col.bad { background: rgba(255, 107, 139, 0.1); border: 1px solid #FF6B8B; }
        
        /* FAQ */
        .faq-item { background: rgba(26, 31, 58, 0.8); padding: 2rem; border-radius: 16px; margin-bottom: 1.5rem; border: 1px solid rgba(0, 212, 255, 0.2); }
        .faq-question { color: #00D4FF; font-weight: 700; font-size: 1.2rem; margin-bottom: 1rem; }
        
        /* Footer */
        footer { padding: 4rem 0; text-align: center; background: rgba(10, 15, 36, 0.95); border-top: 1px solid rgba(0, 212, 255, 0.2); }
        
        /* Responsive */
        @media (max-width: 768px) {
            .hero h1 { font-size: 2.5rem; }
            .section-title { font-size: 2.2rem; }
            .pricing-card.featured { transform: none; }
            .pricing-cards, .features-grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <a href="#" class="logo">AxiomLearn</a>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h1>Master AI Prompt Engineering for Business</h1>
            <p>The 4-Week Sprint Where You Build & Deploy a Custom AI System for Your Actual Job</p>
            <a href="YOUR_GUMROAD_LINK_HERE" class="btn-primary">Join 2026 Cohort - $197 Pre-Sell</a>
            <a href="#" class="btn-secondary">Download Course Syllabus (PDF)</a>
        </div>
    </section>

    <section>
        <div class="container">
            <h2 class="section-title">Why AI Courses Disappoint Professionals</h2>
            <div class="problem-cards">
                <div class="problem-card">
                    <h3>Shallow Theory</h3>
                    <p>Watch videos but never apply to your real work</p>
                </div>
                <div class="problem-card">
                    <h3>No Real Support</h3>
                    <p>Get stuck with AI chatbots instead of human experts</p>
                </div>
                <div class="problem-card">
                    <h3>Hidden Traps</h3>
                    <p>Surprise subscriptions and denied refunds</p>
                </div>
            </div>
        </div>
    </section>

    <section>
        <div class="container">
            <h2 class="section-title">Learn by Building: Your 4-Week Transformation</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-number">1</div>
                    <h3>Week 1: Foundation</h3>
                    <p>Your Custom AI Challenge</p>
                </div>
                <div class="timeline-item">
                    <div class="timeline-number">2</div>
                    <h3>Week 2: Advanced</h3>
                    <p>Personalized Feedback</p>
                </div>
                <div class="timeline-item">
                    <div class="timeline-number">3</div>
                    <h3>Week 3: Automation</h3>
                    <p>Working System Design</p>
                </div>
                <div class="timeline-item">
                    <div class="timeline-number">4</div>
                    <h3>Week 4: Deployment</h3>
                    <p>Portfolio-Ready Project</p>
                </div>
            </div>
            <p style="text-align: center; margin-top: 3rem; color: #B0B7D6; font-size: 1.2rem;">"Each week, you build part of your actual AI workflow"</p>
        </div>
    </section>

    <section>
        <div class="container">
            <h2 class="section-title">Powered by Our AI Mentor System</h2>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">🧠</div>
                    <h3>DepthForge AI</h3>
                    <p>Generates personalized business challenges based on your specific role and industry. No generic exercises.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">⚡</div>
                    <h3>Human-Link Guarantee</h3>
                    <p>Stuck? Book a 30-minute video call with an expert within 24 hours. No ticket queues.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">🛡️</div>
                    <h3>TrustGuard AI</h3>
                    <p>Automatic refunds within 14 days. No hidden subscriptions. One-time payment only.</p>
                </div>
            </div>
        </div>
    </section>

    <section>
        <div class="container">
            <h2 class="section-title">Choose Your Transformation Path</h2>
            <div class="pricing-cards">
                <div class="pricing-card">
                    <h3>Pre-Sell Founder's Access</h3>
                    <div class="price">$197</div>
                    <ul>
                        <li>Lifetime course access</li>
                        <li>3 AI-generated custom projects</li>
                        <li>2× 30-minute founder strategy calls</li>
                        <li>Private community access</li>
                        <li>Early 2026 enrollment</li>
                    </ul>
                    <a href="YOUR_GUMROAD_LINK_HERE" class="btn-primary">Get Founder Pricing</a>
                </div>
                <div class="pricing-card featured">
                    <h3>Standard Enrollment</h3>
                    <div class="price">$497</div>
                    <ul>
                        <li>Lifetime course access</li>
                        <li>3 AI-generated custom projects</li>
                        <li>1× expert review call</li>
                        <li>Private community</li>
                        <li>Official certification</li>
                    </ul>
                    <a href="#" class="btn-primary">Waitlist for Standard</a>
                </div>
                <div class="pricing-card">
                    <h3>Team License</h3>
                    <div class="price">$997</div>
                    <ul>
                        <li>3 team member licenses</li>
                        <li>Team dashboard</li>
                        <li>Group coaching session</li>
                        <li>Custom industry challenges</li>
                    </ul>
                    <a href="#" class="btn-primary">Contact for Teams</a>
                </div>
            </div>
            <p style="text-align: center; margin-top: 3rem; color: #B0B7D6; font-size: 1rem; padding: 1.5rem; background: rgba(26, 31, 58, 0.6); border-radius: 12px; border: 1px solid rgba(0, 212, 255, 0.2);">
                <strong style="color: #00FF9D;">14-Day Zero-Risk Guarantee:</strong> Complete Week 1, if not satisfied, get full refund.
            </p>
        </div>
    </section>

    <section>
        <div class="container">
            <h2 class="section-title">Everything Included in Your Journey</h2>
            <div class="checklist">
                <div class="checklist-item">12 Video Lessons (5-15 min each)</div>
                <div class="checklist-item">3 Custom AI-Generated Business Challenges</div>
                <div class="checklist-item">1 Portfolio-Ready Project</div>
                <div class="checklist-item">4 Weekly Progress Reviews</div>
                <div class="checklist-item">30-Minute Expert Strategy Call</div>
                <div class="checklist-item">Private Community Access</div>
                <div class="checklist-item">Verified Skill Certificate</div>
                <div class="checklist-item">Prompt Library Templates ($500 Value)</div>
                <div class="checklist-item">Lifetime Updates & Access</div>
            </div>
        </div>
    </section>

    <section>
        <div class="container">
            <h2 class="section-title">Designed for Real Professionals</h2>
            <div class="comparison">
                <div class="comparison-col good">
                    <h3 style="color: #00FF9D; font-size: 1.5rem;">✅ PERFECT FOR</h3>
                    <p>Marketing managers</p>
                    <p>Founders & Executives</p>
                    <p>Consultants</p>
                    <p>Team leaders implementing AI</p>
                </div>
                <div class="comparison-col bad">
                    <h3 style="color: #FF6B8B; font-size: 1.5rem;">❌ NOT FOR</h3>
                    <p>"Get rich quick" seekers</p>
                    <p>Unwilling to practice 4-6 hours/week</p>
                    <p>Complete AI beginners</p>
                </div>
            </div>
        </div>
    </section>

    <section>
        <div class="container">
            <h2 class="section-title">2026 Cohort Timeline</h2>
            <div style="background: rgba(26, 31, 58, 0.8); padding: 3rem; border-radius: 20px; margin-top: 2rem; border: 1px solid rgba(0, 212, 255, 0.2); backdrop-filter: blur(10px);">
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem; text-align: center;">
                    <div>
                        <h3 style="color: #00D4FF; font-size: 1.4rem;">Pre-Sell</h3>
                        <p style="color: #B0B7D6; margin: 0.5rem 0;">Now - Jan 31, 2025</p>
                        <p style="color: #00D4FF; font-weight: 700; font-size: 1.2rem;">$197 price</p>
                    </div>
                    <div>
                        <h3 style="color: #00D4FF; font-size: 1.4rem;">Cohort 1 Launch</h3>
                        <p style="color: #B0B7D6; margin: 0.5rem 0;">February 3, 2026</p>
                        <p style="color: #FFD700;">Limited to 100 students</p>
                    </div>
                    <div>
                        <h3 style="color: #00D4FF; font-size: 1.4rem;">Next Cohort</h3>
                        <p style="color: #B0B7D6; margin: 0.5rem 0;">April 2026</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section>
        <div class="container">
            <h2 class="section-title">Frequently Asked Questions</h2>
            <div class="faq-item">
                <div class="faq-question">"When do I get access?"</div>
                <p style="color: #E2E8F0;">Pre-sell buyers get immediate syllabus + strategy call booking. Full course access begins February 2026.</p>
            </div>
            <div class="faq-item">
                <div class="faq-question">"What if I need help?"</div>
                <p style="color: #E2E8F0;">Human-Link Guarantee: Book a 30-minute expert call within 24 hours. Plus community support.</p>
            </div>
            <div class="faq-item">
                <div class="faq-question">"What's required?"</div>
                <p style="color: #E2E8F0;">Computer, internet, 4-6 hours/week, ChatGPT Plus account (we help set up).</p>
            </div>
            <div class="faq-item">
                <div class="faq-question">"Refund policy?"</div>
                <p style="color: #E2E8F0;">14-Day Zero-Risk: Complete Week 1, if not satisfied, email for full refund. No questions.</p>
            </div>
        </div>
    </section>

    <section class="hero">
        <div class="container">
            <h2 style="font-size: 2.8rem;">Build Your AI Advantage Before Your Competitors Do</h2>
            <p style="font-size: 1.3rem; color: #B0B7D6;">"Join 100 professionals transforming their work with AI"</p>
            <a href="YOUR_GUMROAD_LINK_HERE" class="btn-primary" style="margin-top: 2.5rem;">Secure My Founder's Access - $197</a>
            <p style="margin-top: 2rem; font-size: 1rem; color: #B0B7D6; padding: 1rem; background: rgba(0, 212, 255, 0.1); border-radius: 10px; border: 1px solid rgba(0, 212, 255, 0.3);">
                <strong style="color: #00D4FF;">First 10 buyers get:</strong> 1) Price locked forever, 2) Monthly Q&A for 6 months
            </p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p style="font-size: 1.5rem; background: linear-gradient(90deg, #00D4FF, #6C63FF); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-weight: 800; margin-bottom: 1.5rem;">AxiomLearn</p>
            <p style="margin-bottom: 2rem;">
                <a href="#" style="color: #B0B7D6; margin: 0 15px; text-decoration: none; transition: color 0.3s;" onmouseover="this.style.color='#00D4FF'">Contact</a> • 
                <a href="#" style="color: #B0B7D6; margin: 0 15px; text-decoration: none; transition: color 0.3s;" onmouseover="this.style.color='#00D4FF'">Privacy Policy</a> • 
                <a href="#" style="color: #B0B7D6; margin: 0 15px; text-decoration: none; transition: color 0.3s;" onmouseover="this.style.color='#00D4FF'">Terms</a>
            </p>
            <p style="color: #00D4FF; margin-bottom: 2rem;">hello@masteraiprompt.com</p>
            <p style="color: #64748B; font-size: 0.9rem;">© 2025 AxiomLearn. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
