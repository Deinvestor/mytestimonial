<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Oladapo Testimonials</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .testimonial-card {
            background: white;
            border-radius: 20px;
            padding: 40px;
            margin: 30px 0;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            position: relative;
            overflow: hidden;
            width: 600px;
            margin: 30px auto;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .testimonial-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 25px 50px rgba(0,0,0,0.15);
        }
        
        .testimonial-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 6px;
            background: linear-gradient(90deg, #4facfe 0%, #00f2fe 100%);
        }
        
        .quote-icon {
            font-size: 60px;
            color: #4facfe;
            opacity: 0.3;
            position: absolute;
            top: 20px;
            right: 30px;
        }
        
        .testimonial-text {
            font-size: 18px;
            line-height: 1.6;
            color: #333;
            margin-bottom: 30px;
            font-style: italic;
            position: relative;
            z-index: 2;
        }
        
        .client-info {
            display: flex;
            align-items: center;
            gap: 20px;
            border-top: 2px solid #f0f0f0;
            padding-top: 20px;
        }
        
        .client-avatar {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
            font-size: 24px;
        }
        
        .client-details h4 {
            margin: 0;
            font-size: 20px;
            color: #333;
            font-weight: 600;
        }
        
        .client-details p {
            margin: 5px 0 0 0;
            color: #666;
            font-size: 16px;
        }
        
        .expertise-tag {
            position: absolute;
            top: 20px;
            left: 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: 600;
        }
        
        .action-btn {
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
            color: white;
            border: none;
            padding: 12px 24px;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
            font-weight: 600;
            margin: 10px;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        
        .action-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(79, 172, 254, 0.3);
        }
        
        .action-btn:active {
            transform: translateY(0);
        }
        
        .expand-btn {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        
        .expand-btn:hover {
            box-shadow: 0 10px 20px rgba(102, 126, 234, 0.3);
        }
        
        .stars {
            color: #ffd700;
            font-size: 20px;
            margin-bottom: 15px;
        }
        
        h1 {
            text-align: center;
            color: white;
            font-size: 2.5em;
            margin-bottom: 40px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        
        .section-title {
            text-align: center;
            color: white;
            font-size: 1.8em;
            margin: 50px 0 30px 0;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        
        .testimonial-section {
            margin-bottom: 50px;
        }
        
        .additional-testimonials {
            display: none;
            animation: fadeIn 0.5s ease-in-out;
        }
        
        .additional-testimonials.show {
            display: block;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .section-controls {
            text-align: center;
            margin: 30px 0;
        }
        
        .loading {
            text-align: center;
            color: white;
            font-size: 18px;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Clients Testimonials for Oladapo</h1>
        
        <!-- Sales Funnel Expert Section -->
        <div class="testimonial-section">
            <h2 class="section-title">Sales Funnel Expert</h2>
            
            <!-- Main Testimonial -->
            <div class="testimonial-card" id="funnel-testimonial-1">
                <div class="expertise-tag">Sales Funnel Expert</div>
                <div class="quote-icon">"</div>
                <div class="stars">★★★★★</div>
                <div class="testimonial-text">
                    "Working with Oladapo completely transformed our lead generation process. He rebuilt our entire sales funnel and increased our conversion rate by 340% in just 8 weeks. His strategic approach to funnel optimization helped us go from 50 leads per month to over 200 qualified prospects. I can't recommend his funnel expertise enough!"
                </div>
                <div class="client-info">
                    <div class="client-avatar">MJ</div>
                    <div class="client-details">
                        <h4>Michael Johnson</h4>
                        <p>CEO, TechStart Solutions</p>
                    </div>
                </div>
            </div>
            
            <!-- Additional Testimonials (Hidden Initially) -->
            <div class="additional-testimonials" id="funnel-additional">
                <div class="testimonial-card" id="funnel-testimonial-2">
                    <div class="expertise-tag">Sales Funnel Expert</div>
                    <div class="quote-icon">"</div>
                    <div class="stars">★★★★★</div>
                    <div class="testimonial-text">
                        "Oladapo's funnel strategy is genius! He identified bottlenecks in our sales process that we didn't even know existed. After implementing his recommendations, our average order value increased by 180% and our customer lifetime value doubled. The ROI on his services was immediate and substantial."
                    </div>
                    <div class="client-info">
                        <div class="client-avatar">JK</div>
                        <div class="client-details">
                            <h4>Jennifer Kim</h4>
                            <p>Founder, Eco-friendly Products Co.</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card" id="funnel-testimonial-3">
                    <div class="expertise-tag">Sales Funnel Expert</div>
                    <div class="quote-icon">"</div>
                    <div class="stars">★★★★★</div>
                    <div class="testimonial-text">
                        "We were losing 70% of our leads in the middle of our funnel. Oladapo redesigned our entire customer journey and now we're converting 85% of leads into paying customers. His attention to detail and understanding of customer psychology is unmatched."
                    </div>
                    <div class="client-info">
                        <div class="client-avatar">RP</div>
                        <div class="client-details">
                            <h4>Robert Patel</h4>
                            <p>Marketing Manager, Global Consulting</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card" id="funnel-testimonial-4">
                    <div class="expertise-tag">Sales Funnel Expert</div>
                    <div class="quote-icon">"</div>
                    <div class="stars">★★★★★</div>
                    <div class="testimonial-text">
                        "Oladapo turned our struggling funnel into a revenue-generating machine. His A/B testing methodology and data-driven approach helped us achieve a 425% increase in qualified leads. Every business needs someone with his level of funnel expertise."
                    </div>
                    <div class="client-info">
                        <div class="client-avatar">LM</div>
                        <div class="client-details">
                            <h4>Lisa Martinez</h4>
                            <p>VP Sales, Innovation Labs</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card" id="funnel-testimonial-5">
                    <div class="expertise-tag">Sales Funnel Expert</div>
                    <div class="quote-icon">"</div>
                    <div class="stars">★★★★★</div>
                    <div class="testimonial-text">
                        "The funnel optimization Oladapo implemented saved us over $50K in advertising costs while doubling our conversion rates. His systematic approach to funnel analysis and improvement is exactly what growing businesses need."
                    </div>
                    <div class="client-info">
                        <div class="client-avatar">TB</div>
                        <div class="client-details">
                            <h4>Thomas Brown</h4>
                            <p>Director, Digital Solutions Inc.</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="section-controls">
                <button class="action-btn expand-btn" onclick="toggleTestimonials('funnel')">
                    See More Sales Funnel Testimonials
                </button>
                <button class="action-btn" onclick="downloadImage('funnel-testimonial-1', 'Sales-Funnel-Testimonial.png')">
                    Download Testimonial
                </button>
            </div>
        </div>
        
        <!-- GoHighLevel Specialist Section -->
        <div class="testimonial-section">
            <h2 class="section-title">GoHighLevel Specialist</h2>
            
            <!-- Main Testimonial -->
            <div class="testimonial-card" id="ghl-testimonial-1">
                <div class="expertise-tag">GoHighLevel Specialist</div>
                <div class="quote-icon">"</div>
                <div class="stars">★★★★★</div>
                <div class="testimonial-text">
                    "Oladapo is a GoHighLevel wizard! He set up our entire CRM system, automated our follow-up sequences, and integrated everything seamlessly. What used to take our team 20 hours per week now runs automatically. Our client retention improved by 60% thanks to his GHL automation setup."
                </div>
                <div class="client-info">
                    <div class="client-avatar">SR</div>
                    <div class="client-details">
                        <h4>Sarah Rodriguez</h4>
                        <p>Marketing Director, Elite Fitness Studios</p>
                    </div>
                </div>
            </div>
            
            <!-- Additional Testimonials -->
            <div class="additional-testimonials" id="ghl-additional">
                <div class="testimonial-card" id="ghl-testimonial-2">
                    <div class="expertise-tag">GoHighLevel Specialist</div>
                    <div class="quote-icon">"</div>
                    <div class="stars">★★★★★</div>
                    <div class="testimonial-text">
                        "Oladapo's GHL expertise transformed our agency operations. He created custom workflows that automatically nurture leads, book appointments, and follow up with clients. Our close rate increased by 200% and our team efficiency improved dramatically."
                    </div>
                    <div class="client-info">
                        <div class="client-avatar">CW</div>
                        <div class="client-details">
                            <h4>Carlos Williams</h4>
                            <p>Agency Owner, Digital Growth Co.</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card" id="ghl-testimonial-3">
                    <div class="expertise-tag">GoHighLevel Specialist</div>
                    <div class="quote-icon">"</div>
                    <div class="stars">★★★★★</div>
                    <div class="testimonial-text">
                        "The GoHighLevel setup Oladapo created for us is incredible. Automated SMS campaigns, email sequences, and appointment scheduling all work perfectly together. We've seen a 300% increase in qualified appointments since implementation."
                    </div>
                    <div class="client-info">
                        <div class="client-avatar">MH</div>
                        <div class="client-details">
                            <h4>Maria Hernandez</h4>
                            <p>Operations Manager, Real Estate Pros</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card" id="ghl-testimonial-4">
                    <div class="expertise-tag">GoHighLevel Specialist</div>
                    <div class="quote-icon">"</div>
                    <div class="stars">★★★★★</div>
                    <div class="testimonial-text">
                        "Oladapo's mastery of GoHighLevel is unmatched. He integrated our entire tech stack and created automations that handle everything from lead capture to client onboarding. Our revenue per client increased by 150% with his system."
                    </div>
                    <div class="client-info">
                        <div class="client-avatar">JD</div>
                        <div class="client-details">
                            <h4>James Davis</h4>
                            <p>CEO, Service Solutions LLC</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card" id="ghl-testimonial-5">
                    <div class="expertise-tag">GoHighLevel Specialist</div>
                    <div class="quote-icon">"</div>
                    <div class="stars">★★★★★</div>
                    <div class="testimonial-text">
                        "Working with Oladapo on our GHL implementation was the best decision we made this year. His custom pipeline setup and automation workflows helped us scale from 100 to 500 clients without adding staff. Pure genius!"
                    </div>
                    <div class="client-info">
                        <div class="client-avatar">NK</div>
                        <div class="client-details">
                            <h4>Nancy Kumar</h4>
                            <p>Founder, Local Business Hub</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="section-controls">
                <button class="action-btn expand-btn" onclick="toggleTestimonials('ghl')">
                    See More GoHighLevel Testimonials
                </button>
                <button class="action-btn" onclick="downloadImage('ghl-testimonial-1', 'GoHighLevel-Testimonial.png')">
                    Download Testimonial
                </button>
            </div>
        </div>
        
        <!-- Email Marketing Expert Section -->
        <div class="testimonial-section">
            <h2 class="section-title">Email Marketing Expert</h2>
            
            <!-- Main Testimonial -->
            <div class="testimonial-card" id="email-testimonial-1">
                <div class="expertise-tag">Email Marketing Expert</div>
                <div class="quote-icon">"</div>
                <div class="stars">★★★★★</div>
                <div class="testimonial-text">
                    "Our email campaigns were getting 2% open rates before Oladapo stepped in. He completely revamped our email strategy, segmentation, and copy. Now we're seeing 35% open rates and 8% click-through rates consistently. His email marketing expertise generated an additional $75K in revenue in our first quarter working together."
                </div>
                <div class="client-info">
                    <div class="client-avatar">DL</div>
                    <div class="client-details">
                        <h4>David Lee</h4>
                        <p>Founder, Premium Home Decor</p>
                    </div>
                </div>
            </div>
            
            <!-- Additional Testimonials -->
            <div class="additional-testimonials" id="email-additional">
                <div class="testimonial-card" id="email-testimonial-2">
                    <div class="expertise-tag">Email Marketing Expert</div>
                    <div class="quote-icon">"</div>
                    <div class="stars">★★★★★</div>
                    <div class="testimonial-text">
                        "Oladapo's email marketing strategies are revolutionary. He segmented our list and created personalized campaigns that increased our email revenue by 400%. His automated sequences convert cold subscribers into loyal customers effortlessly."
                    </div>
                    <div class="client-info">
                        <div class="client-avatar">AG</div>
                        <div class="client-details">
                            <h4>Ashley Green</h4>
                            <p>Marketing Director, Fashion Forward</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card" id="email-testimonial-3">
                    <div class="expertise-tag">Email Marketing Expert</div>
                    <div class="quote-icon">"</div>
                    <div class="stars">★★★★★</div>
                    <div class="testimonial-text">
                        "The email campaigns Oladapo created for us are pure gold. Our unsubscribe rates dropped by 80% while our engagement soared. He knows exactly how to craft messages that resonate with our audience and drive action."
                    </div>
                    <div class="client-info">
                        <div class="client-avatar">BT</div>
                        <div class="client-details">
                            <h4>Brian Thompson</h4>
                            <p>Owner, Fitness Equipment Plus</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card" id="email-testimonial-4">
                    <div class="expertise-tag">Email Marketing Expert</div>
                    <div class="quote-icon">"</div>
                    <div class="stars">★★★★★</div>
                    <div class="testimonial-text">
                        "Oladapo transformed our email marketing from a cost center to our highest ROI channel. His A/B testing approach and deep understanding of email psychology helped us achieve 45% open rates and 12% click-through rates consistently."
                    </div>
                    <div class="client-info">
                        <div class="client-avatar">RJ</div>
                        <div class="client-details">
                            <h4>Rachel Johnson</h4>
                            <p>CMO, Tech Innovations Inc.</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card" id="email-testimonial-5">
                    <div class="expertise-tag">Email Marketing Expert</div>
                    <div class="quote-icon">"</div>
                    <div class="stars">★★★★★</div>
                    <div class="testimonial-text">
                        "Working with Oladapo on email marketing was a game-changer. He created welcome sequences, nurture campaigns, and re-engagement flows that brought our email list back to life. Our monthly email revenue increased by 320%."
                    </div>
                    <div class="client-info">
                        <div class="client-avatar">KS</div>
                        <div class="client-details">
                            <h4>Kevin Smith</h4>
                            <p>Founder, Online Education Hub</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="section-controls">
                <button class="action-btn expand-btn" onclick="toggleTestimonials('email')">
                    See More Email Marketing Testimonials
                </button>
                <button class="action-btn" onclick="downloadImage('email-testimonial-1', 'Email-Marketing-Testimonial.png')">
                    Download Testimonial
                </button>
            </div>
        </div>
        
        <!-- Copywriting Expert Section -->
        <div class="testimonial-section">
            <h2 class="section-title">Copywriting Expert</h2>
            
            <!-- Main Testimonial -->
            <div class="testimonial-card" id="copy-testimonial-1">
                <div class="expertise-tag">Copywriting Expert</div>
                <div class="quote-icon">"</div>
                <div class="stars">★★★★★</div>
                <div class="testimonial-text">
                    "Oladapo's copy is pure gold. He rewrote our sales pages and email sequences, resulting in a 250% increase in conversions. His understanding of customer psychology and persuasive writing helped us finally connect with our audience. Every word counts, and he knows exactly which words work."
                </div>
                <div class="client-info">
                    <div class="client-avatar">AL</div>
                    <div class="client-details">
                        <h4>Amanda Lopez</h4>
                        <p>Co-Founder, Digital Marketing Academy</p>
                    </div>
                </div>
            </div>
            
            <!-- Additional Testimonials -->
            <div class="additional-testimonials" id="copy-additional">
                <div class="testimonial-card" id="copy-testimonial-2">
                    <div class="expertise-tag">Copywriting Expert</div>
                    <div class="quote-icon">"</div>
                    <div class="stars">★★★★★</div>
                    <div class="testimonial-text">
                        "Oladapo's copywriting skills are exceptional. He transformed our bland product descriptions into compelling stories that sell. Our conversion rates increased by 180% and our average order value went up by 65%. His words literally print money."
                    </div>
                    <div class="client-info">
                        <div class="client-avatar">MW</div>
                        <div class="client-details">
                            <h4>Mark Wilson</h4>
                            <p>CEO, E-commerce Solutions</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card" id="copy-testimonial-3">
                    <div class="expertise-tag">Copywriting Expert</div>
                    <div class="quote-icon">"</div>
                    <div class="stars">★★★★★</div>
                    <div class="testimonial-text">
                        "The sales letters Oladapo wrote for us are masterpieces. He understands our audience better than we do and crafts messages that speak directly to their desires and pain points. Our sales increased by 300% after implementing his copy."
                    </div>
                    <div class="client-info">
                        <div class="client-avatar">JB</div>
                        <div class="client-details">
                            <h4>Jessica Brown</h4>
                            <p>Marketing Manager, Wellness Products</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card" id="copy-testimonial-4">
                    <div class="expertise-tag">Copywriting Expert</div>
                    <div class="quote-icon">"</div>
                    <div class="stars">★★★★★</div>
                    <div class="testimonial-text">
                        "Oladapo's copywriting transformed our entire brand voice. His headlines are magnetic, his body copy is persuasive, and his calls-to-action are irresistible. We've seen a 220% increase in lead generation since working with him."
                    </div>
                    <div class="client-info">
                        <div class="client-avatar">PT</div>
                        <div class="client-details">
                            <h4>Paul Taylor</h4>
                            <p>Founder, Professional Services Co.</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card" id="copy-testimonial-5">
                    <div class="expertise-tag">Copywriting Expert</div>
                    <div class="quote-icon">"</div>
                    <div class="stars">★★★★★</div>
                    <div class="testimonial-text">
                        "Working with Oladapo on copywriting was the best investment we made. His ad copy, landing pages, and email sequences work together seamlessly to guide prospects through our sales process. Our ROI improved by 400%."
                    </div>
                    <div class="client-info">
                        <div class="client-avatar">SM</div>
                        <div class="client-details">
                            <h4>Samantha Miller</h4>
                            <p>Director, Growth Marketing Agency</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="section-controls">
                <button class="action-btn expand-btn" onclick="toggleTestimonials('copy')">
                    See More Copywriting Testimonials
                </button>
                <button class="action-btn" onclick="downloadImage('copy-testimonial-1', 'Copywriting-Testimonial.png')">
                    Download Testimonial
                </button>
            </div>
        </div>
    </div>
    
    <script>
        // Track expanded sections
        const expandedSections = {
            funnel: false,
            ghl: false,
            email: false,
            copy: false
        };
        
        function toggleTestimonials(category) {
            const additionalTestimonials = document.getElementById(category + '-additional');
            const button = event.target;
            
            if (expandedSections[category]) {
                // Collapse
                additionalTestimonials.classList.remove('show');
                expandedSections[category] = false;
                
                // Update button text based on category
                const categoryNames = {
                    funnel: 'Sales Funnel',
                    ghl: 'GoHighLevel',
                    email: 'Email Marketing',
                    copy: 'Copywriting'
                };
                
                button.textContent = `See More ${categoryNames[category]} Testimonials`;
                
                // Scroll to section title
                setTimeout(() => {
                    const sectionTitle = button.closest('.testimonial-section').querySelector('.section-title');
                    sectionTitle.scrollIntoView({ behavior: 'smooth', block: 'start' });
                }, 100);
            } else {
                // Expand
                button.textContent = 'Loading...';
                button.disabled = true;
                
                // Simulate loading time for better UX
                setTimeout(() => {
                    additionalTestimonials.classList.add('show');
                    expandedSections[category] = true;
                    
                    const categoryNames = {
                        funnel: 'Sales Funnel',
                        ghl: 'GoHighLevel',
                        email: 'Email Marketing',
                        copy: 'Copywriting'
                    };
                    
                    button.textContent = `Show Less ${categoryNames[category]} Testimonials`;
                    button.disabled = false;
                    
                    // Scroll to first additional testimonial
                    setTimeout(() => {
                        const firstAdditional = additionalTestimonials.querySelector('.testimonial-card');
                        firstAdditional.scrollIntoView({ behavior: 'smooth', block: 'start' });
                    }, 300);
                }, 800);
            }
        }
        
        function downloadImage(elementId, filename) {
            const element = document.getElementById(elementId);
            const canvas = document.createElement('canvas');
            const ctx = canvas.getContext('2d');
            
            // Set canvas size
            canvas.width = 1200;
            canvas.height = 800;
            
            // Fill background
            ctx.fillStyle = '#ffffff';
            ctx.fillRect(0, 0, canvas.width, canvas.height);
            
            // Add gradient border at top
            const gradient = ctx.createLinearGradient(0, 0, canvas.width, 0);
            gradient.addColorStop(0, '#4facfe');
            gradient.addColorStop(1, '#00f2fe');
            ctx.fillStyle = gradient;
            ctx.fillRect(0, 0, canvas.width, 12);
            
            // Add quote icon
            ctx.fillStyle = 'rgba(79, 172, 254, 0.3)';
            ctx.font = 'bold 120px serif';
            ctx.textAlign = 'right';
            ctx.fillText('"', canvas.width - 60, 140);
            
            // Add expertise tag
            const tagGradient = ctx.createLinearGradient(0, 0, 300, 0);
            tagGradient.addColorStop(0, '#667eea');
            tagGradient.addColorStop(1, '#764ba2');
            ctx.fillStyle = tagGradient;
            ctx.roundRect(40, 40, 300, 50, 25);
            ctx.fill();
            
            ctx.fillStyle = '#ffffff';
            ctx.font = 'bold 18px Arial';
            ctx.textAlign = 'left';
            const tagText = element.querySelector('.expertise-tag').textContent;
            ctx.fillText(tagText, 56, 72);
            
            // Add stars
            ctx.fillStyle = '#ffd700';
            ctx.font = '32px Arial';
            ctx.fillText('★★★★★', 40, 150);
            
            // Add testimonial text
            ctx.fillStyle = '#333333';
            ctx.font = 'italic 24px Arial';
            ctx.textAlign = 'left';
            
            const testimonialText = element.querySelector('.testimonial-text').textContent;
            const words = testimonialText.split(' ');
            let line = '';
            let y = 220;
            const maxWidth = canvas.width - 160;
            
            for (let n = 0; n < words.length; n++) {
                const testLine = line + words[n] + ' ';
                const metrics = ctx.measureText(testLine);
                const testWidth = metrics.width;
                
                if (testWidth > maxWidth && n > 0) {
                    ctx.fillText(line, 80, y);
                    line = words[n] + ' ';
                    y += 40;
                } else {
                    line = testLine;
                }
            }
            ctx.fillText(line, 80, y);
            
            // Add separator line
            ctx.strokeStyle = '#f0f0f0';
            ctx.lineWidth = 4;
            ctx.beginPath();
            ctx.moveTo(80, y + 50);
            ctx.lineTo(canvas.width - 80, y + 50);
            ctx.stroke();
            
            // Add client avatar
            const avatarGradient = ctx.createLinearGradient(0, 0, 120, 120);
            avatarGradient.addColorStop(0, '#4facfe');
            avatarGradient.addColorStop(1, '#00f2fe');
            ctx.fillStyle = avatarGradient;
            ctx.beginPath();
            ctx.arc(140, y + 120, 60, 0, 2 * Math.PI);
            ctx.fill();
            
            // Add client initials
            ctx.fillStyle = '#ffffff';
            ctx.font = 'bold 36px Arial';
            ctx.textAlign = 'center';
            const clientInitials = element.querySelector('.client-avatar').textContent;
            ctx.fillText(clientInitials, 140, y + 130);
            
            // Add client name and title
            ctx.fillStyle = '#333333';
            ctx.font = 'bold 28px Arial';
            ctx.textAlign = 'left';
            const clientName = element.querySelector('.client-details h4').textContent;
            ctx.fillText(clientName, 220, y + 110);
            
            ctx.fillStyle = '#666666';
            ctx.font = '22px Arial';
            const clientTitle = element.querySelector('.client-details p').textContent;
            ctx.fillText(clientTitle, 220, y + 140);
            
            // Convert to blob and download
            canvas.toBlob(function(blob) {
                const url = URL.createObjectURL(blob);
                const a = document.createElement('a');
                a.href = url;
                a.download = filename;
                document.body.appendChild(a);
                a.click();
                document.body.removeChild(a);
                URL.revokeObjectURL(url);
            });
        }
        
        // Add roundRect method if not supported
        if (!CanvasRenderingContext2D.prototype.roundRect) {
            CanvasRenderingContext2D.prototype.roundRect = function(x, y, width, height, radius) {
                this.beginPath();
                this.moveTo(x + radius, y);
                this.lineTo(x + width - radius, y);
                this.quadraticCurveTo(x + width, y, x + width, y + radius);
                this.lineTo(x + width, y + height - radius);
                this.quadraticCurveTo(x + width, y + height, x + width - radius, y + height);
                this.lineTo(x + radius, y + height);
                this.quadraticCurveTo(x, y + height, x, y + height - radius);
                this.lineTo(x, y + radius);
                this.quadraticCurveTo(x, y, x + radius, y);
                this.closePath();
            };
        }
        
        // Add smooth scrolling for better UX
        document.addEventListener('DOMContentLoaded', function() {
            // Add animation on scroll
            const observerOptions = {
                threshold: 0.1,
                rootMargin: '0px 0px -50px 0px'
            };
            
            const observer = new IntersectionObserver(function(entries) {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.style.opacity = '1';
                        entry.target.style.transform = 'translateY(0)';
                    }
                });
            }, observerOptions);
            
            // Observe all testimonial cards
            document.querySelectorAll('.testimonial-card').forEach(card => {
                card.style.opacity = '0';
                card.style.transform = 'translateY(30px)';
                card.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
                observer.observe(card);
            });
            
            // Initial load animation
            setTimeout(() => {
                document.querySelectorAll('.testimonial-card').forEach((card, index) => {
                    if (index < 4) { // Only animate the first 4 cards (main testimonials)
                        setTimeout(() => {
                            card.style.opacity = '1';
                            card.style.transform = 'translateY(0)';
                        }, index * 200);
                    }
                });
            }, 300);
        });
        
        // Add click effects to buttons
        document.addEventListener('click', function(e) {
            if (e.target.classList.contains('action-btn')) {
                e.target.style.transform = 'scale(0.95)';
                setTimeout(() => {
                    e.target.style.transform = '';
                }, 150);
            }
        });
    </script>
</body>
</html>
