# Yoni-sales-page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brain Rot - Stop Doom Scrolling, Start Living</title>
    <style>
        /* CSS Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        html, body {
            overflow-x: hidden;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        
        .container {
            width: 100%;
            max-width: 800px;
            margin: 0 auto;
            padding: 0 2rem;
        }
        
        .section {
            padding: 3rem 0;
        }
        
        .preheader {
            background: #ff6b6b;
            color: white;
            text-align: center;
            padding: 1rem;
            font-weight: bold;
            font-size: 0.9rem;
        }
        
        .hero {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            text-align: center;
            padding: 4rem 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
        
        h1 {
            font-size: 2.5rem;
            font-weight: 900;
            margin-bottom: 1rem;
            line-height: 1.2;
        }
        
        .subheader {
            font-size: 1.3rem;
            margin-bottom: 2rem;
            font-weight: 300;
        }
        
        .vsl-container {
            margin: 2rem 0;
            position: relative;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
        
        .vsl-icon {
            width: 200px;
            height: 120px;
            background: #000;
            border-radius: 10px;
            position: relative;
            cursor: pointer;
            transition: transform 0.3s ease;
            text-decoration: none;
            display: block;
        }
        
        .vsl-icon:hover {
            transform: scale(1.05);
        }
        
        .play-button {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 0;
            height: 0;
            border-left: 20px solid white;
            border-top: 12px solid transparent;
            border-bottom: 12px solid transparent;
        }
        
        .vsl-text {
            color: white;
            margin-top: 1rem;
            font-weight: bold;
            font-size: 0.9rem;
            text-align: center;
        }
        
        .cta-button {
            background: #ff6b6b;
            color: white;
            padding: 1.2rem 2.5rem;
            border: none;
            border-radius: 50px;
            font-size: 1.1rem;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
            text-decoration: none;
            display: inline-block;
            margin: 2rem 0;
        }
        
        .cta-button:hover {
            background: #ff5252;
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(255, 107, 107, 0.3);
        }
        
        h2 {
            font-size: 2rem;
            margin-bottom: 1.5rem;
            color: #333;
            font-weight: 800;
        }
        
        .section-content {
            font-size: 1.1rem;
            line-height: 1.8;
        }
        
        .section-content p {
            margin-bottom: 1.5rem;
        }
        
        .bold {
            font-weight: bold;
        }
        
        .highlight {
            background: #fff3cd;
            padding: 0.2rem 0.4rem;
            border-radius: 3px;
        }
        
        .bullets {
            list-style: none;
            margin: 2rem 0;
        }
        
        .bullets li {
            margin-bottom: 1.5rem;
            padding-left: 1.5rem;
            position: relative;
        }
        
        .bullets li:before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #4CAF50;
            font-weight: bold;
            font-size: 1.2rem;
        }
        
        .testimonial {
            background: #f8f9fa;
            padding: 2rem;
            border-radius: 10px;
            margin: 2rem 0;
            border-left: 4px solid #667eea;
            font-style: italic;
        }
        
        .faq {
            background: #f8f9fa;
            padding: 2rem;
            margin: 2rem 0;
            border-radius: 10px;
        }
        
        .faq-item {
            margin-bottom: 2rem;
        }
        
        .faq-question {
            font-weight: bold;
            font-size: 1.1rem;
            margin-bottom: 0.5rem;
            color: #667eea;
        }
        
        .urgency-box {
            background: #fff3cd;
            border: 2px solid #ffc107;
            padding: 1.5rem;
            border-radius: 10px;
            margin: 2rem 0;
            text-align: center;
        }
        
        /* Mobile Responsiveness */
        @media (max-width: 1024px) {
            .container {
                padding: 0 1.5rem;
            }
            
            h1 {
                font-size: 2.2rem;
            }
            
            .subheader {
                font-size: 1.2rem;
            }
        }
        
        @media (max-width: 768px) {
            .container {
                padding: 0 1rem;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .subheader {
                font-size: 1.1rem;
            }
            
            h2 {
                font-size: 1.7rem;
            }
            
            .section {
                padding: 2rem 0;
            }
            
            .hero {
                padding: 3rem 0;
            }
            
            .vsl-icon {
                width: 160px;
                height: 96px;
            }
            
            .cta-button {
                padding: 1rem 2rem;
                font-size: 1rem;
            }
        }
        
        @media (max-width: 480px) {
            h1 {
                font-size: 1.8rem;
            }
            
            .subheader {
                font-size: 1rem;
            }
            
            h2 {
                font-size: 1.5rem;
            }
            
            .section-content {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <!-- Preheader -->
    <div class="preheader">
        ATTENTION: If you spend 5+ hours daily doom-scrolling your phone...
    </div>
    
    <!-- Hero Section -->
    <div class="hero">
        <div class="container">
            <h1>Cut Your Screen Time By 3+ Hours Daily<br>In Just 7 Days Without Going Cold Turkey</h1>
            <div class="subheader">
                Finally break free from mindless scrolling without missing important messages or feeling disconnected
            </div>
            
            <div class="vsl-container">
                <a href="https://docs.google.com/document/d/1c7qZSw-NpIGYdYc2LoLrt6gyO8WiDGpJ4GTrv2qj5SA/edit?usp=sharing" class="vsl-icon" target="_blank">
                    <div class="play-button"></div>
                </a>
                <div class="vsl-text">Click Here To See The: VSL I WROTE FOR YOU</div>
            </div>
            
            <a href="#offer" class="cta-button">Get Brain Rot FREE - Stop Scrolling Today</a>
        </div>
    </div>
    
    <!-- Problem Identification -->
    <div class="section">
        <div class="container">
            <h2>Your Phone Has Hijacked Your Brain... And You Know It</h2>
            <div class="section-content">
                <p>Right now, your phone is sitting next to you.</p>
                
                <p>You picked it up at least 50 times today. Maybe 100.</p>
                
                <p>You've tried putting it in another room... but somehow it ends up back in your hands within minutes.</p>
                
                <p>You've downloaded those "helpful" screen time apps... only to ignore their warnings and scroll anyway.</p>
                
                <p>You've tried willpower... but 30 seconds into a TikTok spiral, willpower goes out the window.</p>
                
                <p><span class="bold">Sound familiar?</span></p>
                
                <p>Here's what's really happening while you're doom-scrolling:</p>
                
                <p>• Your focus is getting shredded into microscopic pieces<br>
                • Your productivity is bleeding out hour by hour<br>
                • Your relationships are getting the leftover scraps of attention<br>
                • Your goals are gathering dust while you watch strangers live their lives</p>
                
                <p>And the worst part? <span class="highlight">Tomorrow, you'll do it all over again.</span></p>
                
                <p>Unless you keep reading...</p>
                
                <div class="testimonial">
                    "I was spending 7 hours a day on my phone and didn't even realize it. My grades were suffering, I was always tired, and I felt like I was living in a fog. Something had to change." - Sarah, College Student
                </div>
            </div>
        </div>
    </div>
    
    <!-- Origin Story -->
    <div class="section">
        <div class="container">
            <h2>How I Went From 8 Hours of Daily Scrolling to Complete Digital Control</h2>
            <div class="section-content">
                <p>Three years ago, I was the poster child for phone addiction.</p>
                
                <p>8+ hours daily. First thing in the morning, last thing at night.</p>
                
                <p>I missed family dinners because I was watching strangers eat on Instagram.</p>
                
                <p>I'd sit down to work... and three hours later realize I'd accomplished nothing but learning 47 new dance moves I'd never use.</p>
                
                <p><span class="bold">Rock bottom hit when I missed my daughter's first steps</span> because I was deep in a Reddit rabbit hole about conspiracy theories I didn't even care about.</p>
                
                <p>That night, I tried everything:</p>
                
                <p>• App timers (I bypassed them)<br>
                • Putting my phone in a drawer (I retrieved it)<br>
                • Deleting apps (I re-downloaded them)<br>
                • Going cold turkey (lasted 4 hours)</p>
                
                <p>Nothing worked because every solution attacked the symptoms, not the cause.</p>
                
                <p>Then I stumbled onto something that changed everything...</p>
                
                <p><span class="bold">What if instead of fighting my brain, I worked WITH it?</span></p>
                
                <p>What if I could see exactly how my mindless scrolling was rewiring my neural pathways in real-time?</p>
                
                <p>What if breaking the habit felt rewarding instead of punishing?</p>
                
                <p>That revelation led to the creation of something completely different...</p>
            </div>
        </div>
    </div>
    
    <!-- Solution Revelation -->
    <div class="section">
        <div class="container">
            <h2>The "Brain Visualization Method" That Ends Doom-Scrolling Forever</h2>
            <div class="section-content">
                <p>Here's the breakthrough that changes everything:</p>
                
                <p><span class="bold">Your brain needs to SEE the damage to stop the behavior.</span></p>
                
                <p>Traditional apps just tell you "You used your phone for 6 hours today." Big deal. You already knew you had a problem.</p>
                
                <p>But what if you could actually <span class="highlight">watch your brain getting fried in real-time</span>?</p>
                
                <p>What if every swipe, every tap, every mindless scroll showed you exactly how it was fragmenting your focus and stealing your mental clarity?</p>
                
                <p>That's exactly what the Brain Visualization Method does:</p>
                
                <p><span class="bold">STEP 1: REAL-TIME BRAIN IMPACT TRACKING</span><br>
                Every time you pick up your phone, you see a visual representation of what's happening to your neural pathways. Not boring charts. Not guilt-inducing numbers. Actual brain visualization that makes the invisible damage visible.</p>
                
                <p><span class="bold">STEP 2: GAMIFIED FOCUS RECOVERY</span><br>
                Instead of punishing you for phone use, it rewards you for focus. Every minute of undistracted time rebuilds your mental clarity. You literally watch your cognitive power return in real-time.</p>
                
                <p><span class="bold">STEP 3: INTELLIGENT APP INTERVENTION</span><br>
                When it detects mindless scrolling patterns, it doesn't block everything. It intervenes intelligently, keeping your essential functions while stopping the time-wasting spiral before it starts.</p>
                
                <ul class="bullets">
                    <li><span class="bold">A 7-minute morning brain scan</span> that shows you exactly how yesterday's phone use is affecting today's focus → so you start each day with crystal-clear awareness of your mental state → making you the person who's always sharp and present</li>
                    <li><span class="bold">Real-time scroll detection that stops time-wasting before it starts</span> → so you never lose another 3 hours to meaningless content → transforming you into someone who values their time above all else</li>
                    <li><span class="bold">Focus recovery visualization that shows your attention span rebuilding</span> → so you can literally watch yourself getting smarter → becoming the focused, productive person you've always wanted to be</li>
                </ul>
                
                <p><span class="bold">The result?</span></p>
                
                <p>Users report cutting their screen time by 50-70% in the first week. Not through restriction... through awareness.</p>
                
                <div class="testimonial">
                    "I went from 6.5 hours daily to 2.5 hours in just 5 days. But more importantly, those 2.5 hours are intentional. I'm not mindlessly scrolling anymore - I'm using my phone as a tool, not entertainment." - Marcus, Software Engineer
                </div>
            </div>
        </div>
    </div>
    
    <!-- Product Introduction -->
    <div class="section">
        <div class="container">
            <h2>Introducing Brain Rot: Your Personal Focus Coach</h2>
            <div class="section-content">
                <p>After months of development and testing with over 1,000 beta users, Brain Rot is finally here.</p>
                
                <p>This isn't another screen time app that shames you into submission.</p>
                
                <p>This is the world's first app that shows you exactly how your phone habits are reshaping your brain... and guides you back to mental clarity.</p>
                
                <p><span class="bold">Here's what makes Brain Rot different from everything you've tried:</span></p>
                
                <p><span class="bold">VISUAL BRAIN FEEDBACK:</span> Instead of boring time logs, you get real-time visualization of how each tap and swipe affects your cognitive function.</p>
                
                <p><span class="bold">INTELLIGENT INTERVENTION:</span> It doesn't block your phone completely. It learns your patterns and intervenes only when you're falling into mindless scrolling.</p>
                
                <p><span class="bold">FOCUS GAMIFICATION:</span> Every moment of sustained attention rebuilds your mental strength. You literally watch yourself getting more focused.</p>
                
                <p><span class="bold">PERSONALIZED COACHING:</span> Based on your specific phone habits, it provides custom strategies to regain control without feeling restricted.</p>
                
                <p>Compare this to what you've been dealing with:</p>
                
                <p>❌ Generic screen time apps that just show you depressing numbers<br>
                ❌ Harsh app blockers that make you feel punished<br>
                ❌ Willpower-based solutions that fail when you're tired or stressed<br>
                ❌ One-size-fits-all approaches that ignore your unique patterns</p>
                
                <p>VS.</p>
                
                <p>✓ Real-time brain visualization that makes the invisible visible<br>
                ✓ Intelligent intervention that works with your brain, not against it<br>
                ✓ Gamified focus building that feels rewarding, not restrictive<br>
                ✓ Personalized coaching based on your specific usage patterns</p>
                
                <p>The value of reclaiming 4+ hours of your day, every day, for the rest of your life?</p>
                
                <p>Priceless.</p>
            </div>
        </div>
    </div>
    
    <!-- Offer Structure -->
    <div class="section" id="offer">
        <div class="container">
            <h2>Get Complete Control of Your Digital Life... Starting Today</h2>
            <div class="section-content">
                <p>Here's everything you get when you download Brain Rot:</p>
                
                <ul class="bullets">
                    <li><span class="bold">Real-Time Brain Impact Tracker</span> → Instantly see how every phone interaction affects your cognitive function → Become someone who makes conscious choices about their attention</li>
                    <li><span class="bold">Intelligent Doom-Scroll Prevention</span> → Stops mindless scrolling before it starts without blocking essential functions → Transform into a person who uses technology intentionally</li>
                    <li><span class="bold">Focus Recovery Visualization</span> → Watch your attention span rebuild in real-time → Evolve into the sharp, present person you used to be</li>
                    <li><span class="bold">Personalized Digital Wellness Coach</span> → Get custom strategies based on your unique phone habits → Become the master of your digital environment</li>
                    <li><span class="bold">Swipe & Tap Pattern Analysis</span> → Understand the unconscious behaviors driving your phone addiction → Develop into someone with complete self-awareness</li>
                    <li><span class="bold">Daily Focus Challenges</span> → Gamified tasks that strengthen your attention muscle → Become the focused, productive person others admire</li>
                </ul>
                
                <p><span class="bold">Your Investment: FREE to download</span></p>
                
                <p>That's right. You can start reclaiming your life today without spending a penny.</p>
                
                <div class="urgency-box">
                    <p><span class="bold">⚠️ URGENT: iOS Update Coming Soon</span></p>
                    <p>Apple is changing app store policies next month. Download now to ensure you get lifetime access to all current features before potential restrictions take effect.</p>
                </div>
                
                <p><span class="bold">RISK-FREE GUARANTEE:</span> If Brain Rot doesn't cut your mindless scrolling by at least 50% in the first 7 days, simply delete it. No questions asked.</p>
                
                <a href="https://apps.apple.com/app/brain-rot" class="cta-button">Download Brain Rot FREE - Reclaim Your Life Now</a>
            </div>
        </div>
    </div>
    
    <!-- FAQ Section -->
    <div class="section">
        <div class="container">
            <h2>The Questions Everyone Asks Before Reclaiming Their Life</h2>
            <div class="faq">
                <div class="faq-item">
                    <div class="faq-question">Q: "Will this completely block my phone like those other apps?"</div>
                    <p>No. Brain Rot is intelligent. It learns the difference between productive phone use and mindless scrolling. You'll still get important calls, texts, and notifications. It only intervenes when you're falling into time-wasting patterns. This is exactly why Brain Rot succeeds where harsh blockers fail.</p>
                </div>
                
                <div class="faq-item">
                    <div class="faq-question">Q: "What if I need to use social media for work?"</div>
                    <p>Perfect question. Brain Rot distinguishes between intentional use and mindless scrolling. If you're posting for business or checking specific information, it recognizes the pattern and doesn't interfere. It only stops the endless, unconscious scrolling that steals your time. You'll actually become MORE productive at work-related social media tasks.</p>
                </div>
                
                <div class="faq-item">
                    <div class="faq-question">Q: "I've tried screen time apps before and they didn't work..."</div>
                    <p>That's exactly why Brain Rot exists. Traditional apps just show you numbers and expect willpower to do the rest. Brain Rot works WITH your psychology, not against it. When you can literally see your brain getting healthier with each focused moment, change happens naturally. Plus, it's completely free to try.</p>
                </div>
                
                <div class="faq-item">
                    <div class="faq-question">Q: "Is my personal data safe?"</div>
                    <p>Absolutely. Brain Rot is GDPR compliant and processes all data locally on your device. Your usage patterns never leave your phone. We can't see your data even if we wanted to. Your privacy is completely protected while you regain control of your attention.</p>
                </div>
                
                <div class="faq-item">
                    <div class="faq-question">Q: "How quickly will I see results?"</div>
                    <p>Most users notice immediate awareness improvements within hours. The visual brain feedback creates instant consciousness about your habits. Actual behavior change typically happens within 3-7 days as you start making different choices. By week 2, the new patterns feel natural and effortless.</p>
                </div>
                
                <p style="margin-top: 2rem; text-align: center;"><span class="bold">Ready to stop letting your phone control your life?</span></p>
                
                <div style="text-align: center;">
                    <a href="https://apps.apple.com/app/brain-rot" class="cta-button">Download Brain Rot FREE - Take Control Today</a>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
