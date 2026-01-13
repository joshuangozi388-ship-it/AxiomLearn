<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Prompt Engineering for Business: The 4-Week Sprint | MentorAI</title>
    <style>
        /* Modern CSS with animations */
        :root {
            --primary: #0F4C81;
            --accent: #2EC4B6;
            --dark: #0A0F24;
            --light: #F8FAFC;
            --gradient: linear-gradient(135deg, #0F4C81, #2EC4B6);
        }
        
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; }
        body { background: var(--dark); color: var(--light); line-height: 1.6; overflow-x: hidden; }
        
        /* Animated background */
        .bg-animated {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            background: 
                radial-gradient(circle at 20% 80%, rgba(46, 196, 182, 0.1) 0%, transparent 50%),
                radial-gradient(circle at 80% 20%, rgba(15, 76, 129, 0.1) 0%, transparent 50%);
        }
        
        /* Header */
        header {
            padding: 1.5rem 0;
            background: rgba(10, 15, 36, 0.9);
            backdrop-filter: blur(10px);
            position: sticky;
            top: 0;
            z-index: 100;
            border-bottom: 1px solid rgba(46, 196, 182, 0.2);
        }
        
        /* Timeline */
        .timeline-container {
            position: relative;
            padding: 4rem 0;
        }
        
        .timeline-container::before {
            content: '';
            position: absolute;
            left: 50%;
            transform: translateX(-50%);
            width: 2px;
            height: 100%;
            background: var(--gradient);
        }
        
        /* Accordion FAQ */
        .accordion-item {
            background: rgba(15, 76, 129, 0.1);
            border: 1px solid rgba(46, 196, 182, 0.2);
            border-radius: 12px;
            margin-bottom: 1rem;
            overflow: hidden;
        }
        
        .accordion-header {
            padding: 1.5rem;
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-weight: 600;
        }
        
        .accordion-content {
            padding: 0 1.5rem;
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease;
        }
        
        /* Pricing card with strikethrough */
        .price-strikethrough {
            text-decoration: line-through;
            opacity: 0.6;
            margin-right: 10px;
        }
        
        .pricing-card {
            background: rgba(255, 255, 255, 0.05);
            border: 2px solid var(--accent);
            border-radius: 20px;
            padding: 2.5rem;
            position: relative;
            overflow: hidden;
        }
        
        .pricing-card::before {
            content: 'BEST VALUE';
            position: absolute;
            top: 20px;
            right: -30px;
            background: var(--accent);
            color: var(--dark);
            padding: 5px 40px;
            transform: rotate(45deg);
            font-weight: bold;
            font-size: 0.8rem;
        }
        
        /* CTA button */
        .cta-button {
            background: var(--gradient);
            color: white;
            padding: 1.2rem 2.5rem;
            border-radius: 50px;
            font-weight: 600;
            text-decoration: none;
            display: inline-block;
            transition: all 0.3s;
            box-shadow: 0 10px 30px rgba(46, 196, 182, 0.3);
        }
        
        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(46, 196, 182, 0.4);
        }
        
        /* Container */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        section {
            padding: 5rem 0;
        }
        
        /* Hero */
        .hero {
            text-align: center;
            padding: 8rem 0 5rem;
        }
        
        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 1.5rem;
            background: var(--gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            .hero h1 { font-size: 2.5rem; }
            .timeline-container::before { left: 30px; }
        }
    </style>
</head>
<body>
    <div class="bg-animated"></div>
    
    <header>
        <div class="container">
            <div style="display: flex; justify-content: space-between; align-items: center;">
                <div style="font-size: 1.8rem; font-weight: 800; color: var(--accent);">MentorAI</div>
                <div>
                    <a href="#pricing" class="cta-button" style="padding: 0.8rem 1.5rem; font-size: 0.9rem;">Join Waitlist</a>
                </div>
            </div>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <div style="background: rgba(46, 196, 182, 0.1); padding: 0.5rem 1rem; border-radius: 50px; display: inline-block; margin-bottom: 2rem;">
                <span style="color: var(--accent);">Now accepting 2026 cohort</span>
            </div>
            <h1>Master AI Prompt Engineering.<br>Not Just Another Chatbot Course.</h1>
            <p style="font-size: 1.3rem; color: #94A3B8; max-width: 700px; margin: 0 auto 3rem;">
                The 4-week AI-guided sprint where you build and deploy a custom AI system for your actual job.
            </p>
            <a href="#pricing" class="cta-button">Join 2026 Waitlist & Get Syllabus</a>
            <div style="margin-top: 2rem;">
                <a href="#" style="color: var(--accent); text-decoration: none;">Watch a 90-second explainer video →</a>
            </div>
        </div>
    </section>

    <!-- More sections would go here... -->
    
    <section id="pricing">
        <div class="container">
            <h2 style="text-align: center; font-size: 2.5rem; margin-bottom: 3rem;">Founder's Pre-Sell Offer</h2>
            <div class="pricing-card" style="max-width: 500px; margin: 0 auto;">
                <div style="text-align: center;">
                    <div style="font-size: 0.9rem; color: var(--accent); margin-bottom: 1rem;">Limited Time Offer</div>
                    <div style="margin-bottom: 2rem;">
                        <span class="price-strikethrough" style="font-size: 1.5rem;">$297</span>
                        <span style="font-size: 3.5rem; font-weight: 800; color: var(--accent);">$97</span>
                        <div style="color: #94A3B8; font-size: 0.9rem;">Pre-sell price • Save 67%</div>
                    </div>
                    
                    <ul style="list-style: none; text-align: left; margin: 2rem 0;">
                        <li style="padding: 0.8rem 0; border-bottom: 1px solid rgba(255,255,255,0.1);">✅ Lifetime course access</li>
                        <li style="padding: 0.8rem 0; border-bottom: 1px solid rgba(255,255,255,0.1);">✅ 3 AI-generated custom projects</li>
                        <li style="padding: 0.8rem 0; border-bottom: 1px solid rgba(255,255,255,0.1);">✅ 2× 30-minute founder strategy calls</li>
                        <li style="padding: 0.8rem 0; border-bottom: 1px solid rgba(255,255,255,0.1);">✅ Private community access</li>
                        <li style="padding: 0.8rem 0;">✅ Early 2026 enrollment</li>
                    </ul>
                    
                    <a href="YOUR_GUMROAD_LINK_HERE" class="cta-button" style="width: 100%; text-align: center; margin: 2rem 0 1rem;">Buy Now & Get Instant Syllabus Access</a>
                    <div style="font-size: 0.8rem; color: #94A3B8;">Secure checkout powered by Stripe</div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section>
        <div class="container">
            <h2 style="text-align: center; font-size: 2.5rem; margin-bottom: 3rem;">Frequently Asked Questions</h2>
            <div style="max-width: 800px; margin: 0 auto;">
                <div class="accordion-item">
                    <div class="accordion-header" onclick="toggleAccordion(this)">
                        <span>When do I get access?</span>
                        <span>+</span>
                    </div>
                    <div class="accordion-content">
                        <p style="padding: 1rem 0;">Pre-sell buyers get immediate syllabus + strategy call booking. Full course access begins February 2026.</p>
                    </div>
                </div>
                
                <!-- More FAQ items... -->
            </div>
        </div>
    </section>

    <footer style="padding: 3rem 0; text-align: center; border-top: 1px solid rgba(46, 196, 182, 0.2);">
        <div class="container">
            <div style="color: #94A3B8;">© 2025 MentorAI. All rights reserved.</div>
            <div style="margin-top: 1rem;">
                <a href="mailto:hello@mentorai-course.com" style="color: var(--accent); text-decoration: none;">Contact</a>
            </div>
        </div>
    </footer>

    <script>
        // Simple accordion functionality
        function toggleAccordion(header) {
            const content = header.nextElementSibling;
            const isOpen = content.style.maxHeight;
            
            // Close all others
            document.querySelectorAll('.accordion-content').forEach(item => {
                item.style.maxHeight = null;
                item.previousElementSibling.querySelector('span:last-child').textContent = '+';
            });
            
            // Toggle this one
            if (!isOpen) {
                content.style.maxHeight = content.scrollHeight + 'px';
                header.querySelector('span:last-child').textContent = '−';
            }
        }
        
        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({ behavior: 'smooth' });
                }
            });
        });
    </script>
</body>
</html>
