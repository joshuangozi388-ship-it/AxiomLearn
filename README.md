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
</html>
