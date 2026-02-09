<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class 12th Mathematics - UP Board Question Paper 2026</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Georgia', serif;
            background: linear-gradient(135deg, #7c3aed 0%, #a855f7 50%, #ec4899 100%);
            padding: 20px;
            position: relative;
            min-height: 100vh;
        }

        .watermark {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%) rotate(-45deg);
            font-size: 60px;
            color: rgba(255, 255, 255, 0.06);
            font-weight: bold;
            pointer-events: none;
            white-space: nowrap;
            z-index: 1;
            text-align: center;
            line-height: 2;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            background: white;
            padding: 45px;
            border-radius: 12px;
            box-shadow: 0 15px 50px rgba(0,0,0,0.3);
            position: relative;
            z-index: 2;
        }

        .header {
            text-align: center;
            border-bottom: 4px double #7c3aed;
            padding-bottom: 25px;
            margin-bottom: 30px;
            background: linear-gradient(135deg, #ede9fe 0%, #f3e8ff 100%);
            padding: 25px;
            border-radius: 8px;
        }

        .header h1 {
            color: #7c3aed;
            font-size: 28px;
            margin-bottom: 12px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .header h2 {
            color: #a855f7;
            font-size: 21px;
            margin-bottom: 8px;
        }

        .header p {
            color: #475569;
            font-size: 15px;
            margin-top: 12px;
            font-weight: 600;
        }

        .board-logo {
            width: 80px;
            height: 80px;
            margin: 0 auto 15px;
            background: linear-gradient(135deg, #7c3aed, #ec4899);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 36px;
            font-weight: bold;
        }

        .instructions {
            background: linear-gradient(135deg, #fef3c7 0%, #fde68a 100%);
            padding: 18px;
            border-radius: 8px;
            margin-bottom: 28px;
            border-left: 5px solid #f59e0b;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        .instructions h3 {
            color: #92400e;
            margin-bottom: 12px;
            font-size: 17px;
            display: flex;
            align-items: center;
        }

        .instructions h3::before {
            content: "📐";
            margin-right: 8px;
        }

        .instructions ul {
            margin-left: 25px;
            color: #78350f;
        }

        .instructions li {
            margin-bottom: 6px;
            font-size: 14px;
            line-height: 1.5;
        }

        .section {
            margin-bottom: 35px;
        }

        .section-title {
            background: linear-gradient(135deg, #7c3aed 0%, #a855f7 100%);
            color: white;
            padding: 14px 22px;
            border-radius: 8px;
            font-size: 18px;
            margin-bottom: 22px;
            font-weight: bold;
            box-shadow: 0 4px 12px rgba(124, 58, 237, 0.3);
            display: flex;
            align-items: center;
        }

        .section-title::before {
            content: "∑";
            margin-right: 10px;
            font-size: 28px;
            font-weight: bold;
        }

        .question {
            margin-bottom: 28px;
            padding: 18px;
            background: #f8fafc;
            border-radius: 8px;
            border-left: 4px solid #a855f7;
            box-shadow: 0 2px 6px rgba(0,0,0,0.05);
            transition: all 0.3s ease;
        }

        .question:hover {
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            transform: translateX(3px);
        }

        .question-number {
            font-weight: bold;
            color: #7c3aed;
            margin-bottom: 10px;
            font-size: 16px;
        }

        .question-text {
            color: #1e293b;
            line-height: 1.7;
            font-size: 15px;
        }

        .marks {
            float: right;
            background: linear-gradient(135deg, #10b981, #059669);
            color: white;
            padding: 4px 12px;
            border-radius: 15px;
            font-size: 13px;
            font-weight: bold;
            box-shadow: 0 2px 6px rgba(16, 185, 129, 0.3);
        }

        .or-option {
            margin-top: 15px;
            padding-top: 15px;
            border-top: 2px dashed #cbd5e0;
            color: #7c3aed;
            font-weight: 600;
        }

        .or-option::before {
            content: "OR / अथवा";
            display: block;
            text-align: center;
            margin-bottom: 10px;
            font-size: 14px;
            color: #a855f7;
        }

        .answer-space {
            margin-top: 18px;
            padding: 12px;
            background: white;
            border: 2px dashed #cbd5e0;
            border-radius: 6px;
            min-height: 90px;
        }

        .medium-answer {
            min-height: 130px;
        }

        .long-answer {
            min-height: 180px;
        }

        .very-long-answer {
            min-height: 220px;
        }

        .unit-tag {
            display: inline-block;
            background: #ede9fe;
            color: #7c3aed;
            padding: 3px 10px;
            border-radius: 12px;
            font-size: 11px;
            margin-left: 8px;
            font-weight: 600;
        }

        .important-note {
            background: #fef2f2;
            border-left: 4px solid #ef4444;
            padding: 12px;
            margin: 20px 0;
            border-radius: 4px;
            color: #991b1b;
            font-size: 14px;
        }

        .formula-box {
            background: #f0fdf4;
            border: 1px solid #86efac;
            padding: 10px;
            margin: 10px 0;
            border-radius: 4px;
            font-family: 'Courier New', monospace;
            color: #166534;
        }

        .footer {
            text-align: center;
            margin-top: 45px;
            padding-top: 25px;
            border-top: 3px solid #e2e8f0;
            color: #64748b;
            font-size: 14px;
        }

        .creator {
            margin-top: 12px;
            font-weight: bold;
            background: linear-gradient(135deg, #7c3aed, #ec4899);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            font-size: 17px;
        }

        @media print {
            body {
                background: white;
            }
            .watermark {
                color: rgba(0, 0, 0, 0.03);
            }
            .question {
                break-inside: avoid;
            }
        }

        @media (max-width: 768px) {
            .container {
                padding: 25px;
            }
            .header h1 {
                font-size: 22px;
            }
        }
    </style>
</head>
<body>
    <div class="watermark">
        ANMOL SINGH<br>
        IG: rajput_anmolsingh3<br>
        MATHS 2026
    </div>

    <div class="container">
        <div class="header">
            <div class="board-logo">UP</div>
            <h1>Uttar Pradesh Madhyamik Shiksha Parishad</h1>
            <h2>Intermediate Examination - 2026</h2>
            <h2>Subject: Mathematics (गणित)</h2>
            <p><strong>Class:</strong> XII (Intermediate) | <strong>Time:</strong> 3 Hours 15 Minutes | <strong>Maximum Marks:</strong> 100</p>
        </div>

        <div class="instructions">
            <h3>सामान्य निर्देश / General Instructions</h3>
            <ul>
                <li>All questions are compulsory / सभी प्रश्न अनिवार्य हैं</li>
                <li>First 15 minutes are allotted for reading the question paper / प्रथम 15 मिनट प्रश्न-पत्र पढ़ने के लिए निर्धारित हैं</li>
                <li>Internal choice is given in some questions / कुछ प्रश्नों में आंतरिक विकल्प दिया गया है</li>
                <li>Use of calculator is not permitted / कैलकुलेटर का प्रयोग वर्जित है</li>
                <li>Draw neat diagrams wherever required / जहाँ आवश्यक हो स्वच्छ चित्र बनाइए</li>
                <li>Show all the steps in numerical problems / संख्यात्मक प्रश्नों में सभी पद दर्शाइए</li>
                <li>Write your roll number on the answer sheet / उत्तर पुस्तिका पर अनुक्रमांक अवश्य लिखें</li>
            </ul>
        </div>

        <!-- Section A: Very Short Answer Questions (1 Mark Each) -->
        <div class="section">
            <div class="section-title">खंड - अ / Section A: अति लघु उत्तरीय प्रश्न (1 Mark Each)</div>

            <div class="question">
                <div class="question-number">Q1. <span class="unit-tag">Relations</span><span class="marks">1 Mark</span></div>
                <div class="question-text">Define a reflexive relation.<br>
                स्वतुल्य संबंध को परिभाषित कीजिए।</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q2. <span class="unit-tag">Functions</span><span class="marks">1 Mark</span></div>
                <div class="question-text">What is the domain of f(x) = 1/x?<br>
                f(x) = 1/x का प्रांत क्या है?</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q3. <span class="unit-tag">Inverse Trig</span><span class="marks">1 Mark</span></div>
                <div class="question-text">Find the principal value of sin⁻¹(1/2).<br>
                sin⁻¹(1/2) का मुख्य मान ज्ञात कीजिए।</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q4. <span class="unit-tag">Matrices</span><span class="marks">1 Mark</span></div>
                <div class="question-text">What is the order of a matrix with 12 elements arranged in 3 rows?<br>
                3 पंक्तियों में व्यवस्थित 12 अवयवों वाले आव्यूह की कोटि क्या है?</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q5. <span class="unit-tag">Determinants</span><span class="marks">1 Mark</span></div>
                <div class="question-text">If A is a square matrix of order 3 and |A| = 5, find |2A|.<br>
                यदि A कोटि 3 का एक वर्ग आव्यूह है और |A| = 5 है, तो |2A| ज्ञात कीजिए।</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q6. <span class="unit-tag">Continuity</span><span class="marks">1 Mark</span></div>
                <div class="question-text">Is f(x) = |x| continuous at x = 0?<br>
                क्या f(x) = |x|, x = 0 पर सतत है?</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q7. <span class="unit-tag">Differentiation</span><span class="marks">1 Mark</span></div>
                <div class="question-text">Find dy/dx if y = eˣ.<br>
                यदि y = eˣ है, तो dy/dx ज्ञात कीजिए।</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q8. <span class="unit-tag">Integration</span><span class="marks">1 Mark</span></div>
                <div class="question-text">Evaluate: ∫cos x dx<br>
                समाकलन कीजिए: ∫cos x dx</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q9. <span class="unit-tag">Vectors</span><span class="marks">1 Mark</span></div>
                <div class="question-text">Find the unit vector in the direction of vector i + j + k.<br>
                सदिश i + j + k की दिशा में इकाई सदिश ज्ञात कीजिए।</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q10. <span class="unit-tag">3D Geometry</span><span class="marks">1 Mark</span></div>
                <div class="question-text">Write the direction cosines of the x-axis.<br>
                x-अक्ष की दिक्-कोज्याएँ लिखिए।</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q11. <span class="unit-tag">LPP</span><span class="marks">1 Mark</span></div>
                <div class="question-text">What is the feasible region in Linear Programming?<br>
                रैखिक प्रोग्रामन में सुसंगत क्षेत्र क्या है?</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q12. <span class="unit-tag">Probability</span><span class="marks">1 Mark</span></div>
                <div class="question-text">If P(A) = 0.5 and P(B) = 0.4, find P(A ∪ B) if A and B are mutually exclusive events.<br>
                यदि P(A) = 0.5 और P(B) = 0.4 है, तो P(A ∪ B) ज्ञात कीजिए जब A और B परस्पर अपवर्जी घटनाएँ हैं।</div>
                <div class="answer-space"></div>
            </div>
        </div>

        <!-- Section B: Short Answer Questions (2 Marks Each) -->
        <div class="section">
            <div class="section-title">खंड - ब / Section B: लघु उत्तरीय प्रश्न (2 Marks Each)</div>

            <div class="question">
                <div class="question-number">Q13. <span class="unit-tag">Relations</span><span class="marks">2 Marks</span></div>
                <div class="question-text">Check whether the relation R = {(1,1), (2,2), (3,3)} on set A = {1, 2, 3} is reflexive or not.<br>
                जाँच कीजिए कि समुच्चय A = {1, 2, 3} पर संबंध R = {(1,1), (2,2), (3,3)} स्वतुल्य है या नहीं।</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q14. <span class="unit-tag">Functions</span><span class="marks">2 Marks</span></div>
                <div class="question-text">Show that the function f: R → R defined by f(x) = 2x + 3 is one-one.<br>
                दर्शाइए कि फलन f: R → R जो f(x) = 2x + 3 द्वारा परिभाषित है, एकैकी है।</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q15. <span class="unit-tag">Inverse Trig</span><span class="marks">2 Marks</span></div>
                <div class="question-text">Prove that: tan⁻¹(1) + cos⁻¹(-1/2) = 13π/12<br>
                सिद्ध कीजिए: tan⁻¹(1) + cos⁻¹(-1/2) = 13π/12</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q16. <span class="unit-tag">Matrices</span><span class="marks">2 Marks</span></div>
                <div class="question-text">If A = [1 2; 3 4] and B = [2 0; 1 3], find A + B.<br>
                यदि A = [1 2; 3 4] और B = [2 0; 1 3] है, तो A + B ज्ञात कीजिए।</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q17. <span class="unit-tag">Determinants</span><span class="marks">2 Marks</span></div>
                <div class="question-text">Find the value of determinant |1 2; 3 4|.<br>
                सारणिक |1 2; 3 4| का मान ज्ञात कीजिए।</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q18. <span class="unit-tag">Continuity</span><span class="marks">2 Marks</span></div>
                <div class="question-text">Examine the continuity of f(x) = x² at x = 2.<br>
                f(x) = x² की सततता x = 2 पर जाँचिए।</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q19. <span class="unit-tag">Differentiation</span><span class="marks">2 Marks</span></div>
                <div class="question-text">Differentiate x³ + 3x² + 2x + 1 with respect to x.<br>
                x³ + 3x² + 2x + 1 का x के सापेक्ष अवकलन कीजिए।</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q20. <span class="unit-tag">Integration</span><span class="marks">2 Marks</span></div>
                <div class="question-text">Evaluate: ∫(2x + 3) dx<br>
                समाकलन कीजिए: ∫(2x + 3) dx</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q21. <span class="unit-tag">Vectors</span><span class="marks">2 Marks</span></div>
                <div class="question-text">Find the magnitude of vector 3i + 4j.<br>
                सदिश 3i + 4j का परिमाण ज्ञात कीजिए।</div>
                <div class="answer-space"></div>
            </div>

            <div class="question">
                <div class="question-number">Q22. <span class="unit-tag">Probability</span><span class="marks">2 Marks</span></div>
                <div class="question-text">A coin is tossed twice. Find the probability of getting at least one head.<br>
                एक सिक्के को दो बार उछाला जाता है। कम से कम एक चित आने की प्रायिकता ज्ञात कीजिए।</div>
                <div class="answer-space"></div>
            </div>
        </div>

        <!-- Section C: Long Answer Questions - Part I (4 Marks Each) -->
        <div class="section">
            <div class="section-title">खंड - स (भाग 1) / Section C (Part 1): दीर्घ उत्तरीय प्रश्न (4 Marks Each)</div>

            <div class="question">
                <div class="question-number">Q23. <span class="unit-tag">Relations</span><span class="marks">4 Marks</span></div>
                <div class="question-text">Show that the relation R on the set A = {1, 2, 3} defined by R = {(1,1), (2,2), (3,3), (1,2), (2,3)} is reflexive and transitive but not symmetric.<br>
                दर्शाइए कि समुच्चय A = {1, 2, 3} पर संबंध R = {(1,1), (2,2), (3,3), (1,2), (2,3)} स्वतुल्य और संक्रामक है परंतु सममित नहीं है।</div>
                <div class="answer-space medium-answer"></div>
            </div>

            <div class="question">
                <div class="question-number">Q24. <span class="unit-tag">Inverse Trig</span><span class="marks">4 Marks</span></div>
                <div class="question-text">Prove that: 2tan⁻¹(1/2) + tan⁻¹(1/7) = tan⁻¹(31/17)<br>
                सिद्ध कीजिए: 2tan⁻¹(1/2) + tan⁻¹(1/7) = tan⁻¹(31/17)
                <div class="or-option">
                    Prove that: sin⁻¹(3/5) + cos⁻¹(12/13) = sin⁻¹(56/65)<br>
                    सिद्ध कीजिए: sin⁻¹(3/5) + cos⁻¹(12/13) = sin⁻¹(56/65)
                </div>
                </div>
                <div class="answer-space medium-answer"></div>
            </div>

            <div class="question">
                <div class="question-number">Q25. <span class="unit-tag">Matrices</span><span class="marks">4 Marks</span></div>
                <div class="question-text">If A = [1 2 3; 2 3 1; 3 1 2], verify that A(adj A) = |A|I.<br>
                यदि A = [1 2 3; 2 3 1; 3 1 2] है, तो सत्यापित कीजिए कि A(adj A) = |A|I.</div>
                <div class="answer-space medium-answer"></div>
            </div>

            <div class="question">
                <div class="question-number">Q26. <span class="unit-tag">Determinants</span><span class="marks">4 Marks</span></div>
                <div class="question-text">Using properties of determinants, prove that:<br>
                |a b c; b c a; c a b| = 3abc - a³ - b³ - c³<br>
                सारणिकों के गुणों का उपयोग करके सिद्ध कीजिए:<br>
                |a b c; b c a; c a b| = 3abc - a³ - b³ - c³</div>
                <div class="answer-space medium-answer"></div>
            </div>

            <div class="question">
                <div class="question-number">Q27. <span class="unit-tag">Continuity</span><span class="marks">4 Marks</span></div>
                <div class="question-text">Discuss the continuity of the function f(x) = |x| + |x - 1| at x = 0 and x = 1.<br>
                फलन f(x) = |x| + |x - 1| की सततता x = 0 और x = 1 पर विवेचना कीजिए।
                <div class="or-option">
                    Find the value of k if f(x) = {x² - 4 / x - 2, if x ≠ 2; k, if x = 2} is continuous at x = 2.<br>
                    k का मान ज्ञात कीजिए यदि f(x) = {x² - 4 / x - 2, यदि x ≠ 2; k, यदि x = 2} x = 2 पर सतत है।
                </div>
                </div>
                <div class="answer-space medium-answer"></div>
            </div>

            <div class="question">
                <div class="question-number">Q28. <span class="unit-tag">Differentiation</span><span class="marks">4 Marks</span></div>
                <div class="question-text">If y = tan⁻¹(√(1+x²) - 1)/x, prove that dy/dx = 1/(2(1+x²)).<br>
                यदि y = tan⁻¹(√(1+x²) - 1)/x है, तो सिद्ध कीजिए कि dy/dx = 1/(2(1+x²))।</div>
                <div class="answer-space medium-answer"></div>
            </div>

            <div class="question">
                <div class="question-number">Q29. <span class="unit-tag">Integration</span><span class="marks">4 Marks</span></div>
                <div class="question-text">Evaluate: ∫x²/(x² + 4)(x² + 9) dx<br>
                समाकलन कीजिए: ∫x²/(x² + 4)(x² + 9) dx
                <div class="or-option">
                    Evaluate: ∫dx/(x² + 2x + 5)<br>
                    समाकलन कीजिए: ∫dx/(x² + 2x + 5)
                </div>
                </div>
                <div class="answer-space medium-answer"></div>
            </div>

            <div class="question">
                <div class="question-number">Q30. <span class="unit-tag">Vectors</span><span class="marks">4 Marks</span></div>
                <div class="question-text">Find the angle between vectors a = 2i + j - 2k and b = i + j + k.<br>
                सदिशों a = 2i + j - 2k और b = i + j + k के बीच का कोण ज्ञात कीजिए।</div>
                <div class="answer-space medium-answer"></div>
            </div>
        </div>

        <!-- Section C: Long Answer Questions - Part II (6 Marks Each) -->
        <div class="section">
            <div class="section-title">खंड - स (भाग 2) / Section C (Part 2): दीर्घ उत्तरीय प्रश्न (6 Marks Each)</div>

            <div class="question">
                <div class="question-number">Q31. <span class="unit-tag">Functions</span><span class="marks">6 Marks</span></div>
                <div class="question-text">Show that the function f: R → R defined by f(x) = 3x + 5 is bijective. Find its inverse function.<br>
                दर्शाइए कि फलन f: R → R जो f(x) = 3x + 5 द्वारा परिभाषित है, द्विआधारी है। इसका प्रतिलोम फलन ज्ञात कीजिए।</div>
                <div class="answer-space long-answer"></div>
            </div>

            <div class="question">
                <div class="question-number">Q32. <span class="unit-tag">Matrices</span><span class="marks">6 Marks</span></div>
                <div class="question-text">Using elementary row operations, find the inverse of matrix A = [2 3 1; 1 2 2; 3 1 -1].<br>
                पंक्ति रूपांतरण का उपयोग करके आव्यूह A = [2 3 1; 1 2 2; 3 1 -1] का प्रतिलोम ज्ञात कीजिए।
                <div class="or-option">
                    Solve the system of equations using matrix method:<br>
                    x + y + z = 6, x - y + z = 2, 2x + y - z = 1<br>
                    आव्यूह विधि से समीकरणों को हल कीजिए:<br>
                    x + y + z = 6, x - y + z = 2, 2x + y - z = 1
                </div>
                </div>
                <div class="answer-space long-answer"></div>
            </div>

            <div class="question">
                <div class="question-number">Q33. <span class="unit-tag">Differentiation</span><span class="marks">6 Marks</span></div>
                <div class="question-text">If x = a(cos t + t sin t) and y = a(sin t - t cos t), find d²y/dx².<br>
                यदि x = a(cos t + t sin t) और y = a(sin t - t cos t) है, तो d²y/dx² ज्ञात कीजिए।</div>
                <div class="answer-space long-answer"></div>
            </div>

            <div class="question">
                <div class="question-number">Q34. <span class="unit-tag">Application of Derivatives</span><span class="marks">6 Marks</span></div>
                <div class="question-text">Find the maximum and minimum values of the function f(x) = x³ - 3x² - 9x + 12.<br>
                फलन f(x) = x³ - 3x² - 9x + 12 के उच्चतम और निम्नतम मान ज्ञात कीजिए।
                <div class="or-option">
                    Prove that the semi-vertical angle of a cone of maximum volume and given slant height is tan⁻¹(√2).<br>
                    सिद्ध कीजिए कि दी गई तिर्यक ऊँचाई और अधिकतम आयतन वाले शंकु का अर्ध-शीर्ष कोण tan⁻¹(√2) है।
                </div>
                </div>
                <div class="answer-space long-answer"></div>
            </div>

            <div class="question">
                <div class="question-number">Q35. <span class="unit-tag">Integration</span><span class="marks">6 Marks</span></div>
                <div class="question-text">Evaluate: ∫₀^(π/2) x sin x dx<br>
                समाकलन कीजिए: ∫₀^(π/2) x sin x dx
                <div class="or-option">
                    Evaluate: ∫₁³ (2x² + 5x) dx<br>
                    समाकलन कीजिए: ∫₁³ (2x² + 5x) dx
                </div>
                </div>
                <div class="answer-space long-answer"></div>
            </div>

            <div class="question">
                <div class="question-number">Q36. <span class="unit-tag">Differential Equations</span><span class="marks">6 Marks</span></div>
                <div class="question-text">Solve the differential equation: dy/dx + y = e^x<br>
                अवकल समीकरण हल कीजिए: dy/dx + y = e^x
                <div class="or-option">
                    Solve: (x² - y²)dx + 2xy dy = 0<br>
                    हल कीजिए: (x² - y²)dx + 2xy dy = 0
                </div>
                </div>
                <div class="answer-space long-answer"></div>
            </div>

            <div class="question">
                <div class="question-number">Q37. <span class="unit-tag">Vectors</span><span class="marks">6 Marks</span></div>
                <div class="question-text">Prove that [a + b, b + c, c + a] = 2[a b c], where a, b, c are vectors.<br>
                सिद्ध कीजिए कि [a + b, b + c, c + a] = 2[a b c], जहाँ a, b, c सदिश हैं।</div>
                <div class="answer-space long-answer"></div>
            </div>

            <div class="question">
                <div class="question-number">Q38. <span class="unit-tag">3D Geometry</span><span class="marks">6 Marks</span></div>
                <div class="question-text">Find the equation of the line passing through the point (1, 2, 3) and parallel to the line (x-1)/2 = (y+1)/3 = (z-2)/4.<br>
                बिंदु (1, 2, 3) से होकर जाने वाली और रेखा (x-1)/2 = (y+1)/3 = (z-2)/4 के समांतर रेखा का समीकरण ज्ञात कीजिए।
                <div class="or-option">
                    Find the shortest distance between the lines:<br>
                    r = i + 2j + 3k + λ(2i + 3j + 4k) and r = 2i + 4j + 5k + μ(3i + 4j + 5k)<br>
                    रेखाओं के बीच न्यूनतम दूरी ज्ञात कीजिए:<br>
                    r = i + 2j + 3k + λ(2i + 3j + 4k) और r = 2i + 4j + 5k + μ(3i + 4j + 5k)
                </div>
                </div>
                <div class="answer-space long-answer"></div>
            </div>
        </div>

        <!-- Section D: Very Long Answer Questions (8 Marks Each) -->
        <div class="section">
            <div class="section-title">खंड - द / Section D: अति दीर्घ उत्तरीय प्रश्न (8 Marks Each)</div>

            <div class="question">
                <div class="question-number">Q39. <span class="unit-tag">Application of Integrals</span><span class="marks">8 Marks</span></div>
                <div class="question-text">Find the area of the region bounded by the curve y² = 4x and the line y = 2x - 4.<br>
                वक्र y² = 4x और रेखा y = 2x - 4 से घिरे क्षेत्र का क्षेत्रफल ज्ञात कीजिए।
                <div class="or-option">
                    Using integration, find the area of the circle x² + y² = 16.<br>
                    समाकलन का उपयोग करके वृत्त x² + y² = 16 का क्षेत्रफल ज्ञात कीजिए।
                </div>
                </div>
                <div class="answer-space very-long-answer"></div>
            </div>

            <div class="question">
                <div class="question-number">Q40. <span class="unit-tag">3D Geometry</span><span class="marks">8 Marks</span></div>
                <div class="question-text">Find the equation of the plane passing through the points (1, 1, 1), (1, -1, 1) and (-7, -3, -5).<br>
                बिंदुओं (1, 1, 1), (1, -1, 1) और (-7, -3, -5) से होकर जाने वाले समतल का समीकरण ज्ञात कीजिए।</div>
                <div class="answer-space very-long-answer"></div>
            </div>

            <div class="question">
                <div class="question-number">Q41. <span class="unit-tag">LPP</span><span class="marks">8 Marks</span></div>
                <div class="question-text">Maximize Z = 3x + 4y subject to the constraints:<br>
                x + y ≤ 4, x + 2y ≤ 6, x ≥ 0, y ≥ 0<br>
                Solve graphically.<br>
                Z = 3x + 4y का अधिकतमीकरण कीजिए, प्रतिबंध:<br>
                x + y ≤ 4, x + 2y ≤ 6, x ≥ 0, y ≥ 0<br>
                आलेखीय विधि से हल कीजिए।</div>
                <div class="answer-space very-long-answer"></div>
            </div>

            <div class="question">
                <div class="question-number">Q42. <span class="unit-tag">Probability</span><span class="marks">8 Marks</span></div>
                <div class="question-text">A bag contains 5 red and 3 blue balls. Two balls are drawn at random without replacement. Find the probability distribution of the number of red balls drawn. Also find the mean and variance.<br>
                एक थैले में 5 लाल और 3 नीली गेंदें हैं। बिना प्रतिस्थापन के दो गेंदें यादृच्छिक रूप से निकाली जाती हैं। निकाली गई लाल गेंदों की संख्या का प्रायिकता बंटन ज्ञात कीजिए। माध्य और प्रसरण भी ज्ञात कीजिए।
                <div class="or-option">
                    A die is thrown 6 times. If getting an odd number is a success, find the probability of:<br>
                    (i) exactly 5 successes (ii) at least 5 successes (iii) at most 5 successes<br>
                    एक पासे को 6 बार फेंका जाता है। यदि विषम संख्या आना सफलता है, तो प्रायिकता ज्ञात कीजिए:<br>
                    (i) ठीक 5 सफलताएँ (ii) कम से कम 5 सफलताएँ (iii) अधिक से अधिक 5 सफलताएँ
                </div>
                </div>
                <div class="answer-space very-long-answer"></div>
            </div>
        </div>

        <div class="important-note">
            <strong>📐 Important Note / महत्वपूर्ण सूचना:</strong><br>
            • All steps must be shown clearly in calculations (गणनाओं में सभी पद स्पष्ट रूप से दर्शाने चाहिए)<br>
            • Formulas used must be written (प्रयुक्त सूत्र लिखने चाहिए)<br>
            • Draw graphs on graph paper wherever required (जहाँ आवश्यक हो ग्राफ पेपर पर आलेख बनाएँ)<br>
            • Answers should be in simplified form (उत्तर सरलीकृत रूप में होने चाहिए)
        </div>

        <div class="footer">
            <p><strong>*** शुभकामनाएँ / Best Wishes ***</strong></p>
            <p style="margin: 10px 0; font-style: italic; color: #7c3aed;">"Mathematics is not about numbers, equations, or algorithms. It is about understanding."</p>
            <div class="creator">∫ Created by: Anmol Singh | IG: @rajput_anmolsingh3 ∫</div>
            <p style="margin-top: 8px; font-size: 12px; color: #94a3b8;">For educational purposes only | केवल शैक्षिक उद्देश्यों के लिए</p>
        </div>
    </div>
</body>
</html>
