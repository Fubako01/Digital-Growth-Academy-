# Digital-Growth-Academy-
Website for digital growth academy 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Student Registration | Digital Growth Academy</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f4f7f6;
            color: #222;
            line-height: 1.6;
        }

        header {
            background: #0b6b4f;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            font-size: 26px;
            margin-bottom: 5px;
        }

        header p {
            font-size: 14px;
        }

        .container {
            width: 92%;
            max-width: 850px;
            margin: 30px auto;
        }

        .registration-card {
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
        }

        .registration-card h2 {
            color: #0b6b4f;
            margin-bottom: 10px;
        }

        .intro {
            margin-bottom: 25px;
            color: #555;
        }

        .section-title {
            margin-top: 25px;
            margin-bottom: 15px;
            padding-bottom: 8px;
            border-bottom: 2px solid #e5e5e5;
            color: #0b6b4f;
        }

        label {
            display: block;
            font-weight: bold;
            margin-top: 15px;
            margin-bottom: 6px;
        }

        input,
        select,
        textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #ccc;
            border-radius: 7px;
            font-size: 15px;
        }

        textarea {
            min-height: 110px;
            resize: vertical;
        }

        input:focus,
        select:focus,
        textarea:focus {
            outline: none;
            border-color: #0b6b4f;
        }

        .checkbox-group {
            margin-top: 10px;
        }

        .checkbox-item {
            margin: 9px 0;
        }

        .checkbox-item label {
            display: inline;
            font-weight: normal;
            margin-left: 7px;
        }

        .agreement {
            background: #f0f8f5;
            padding: 18px;
            border-radius: 8px;
            margin-top: 20px;
        }

        .submit-btn {
            width: 100%;
            margin-top: 25px;
            padding: 14px;
            background: #0b6b4f;
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 17px;
            font-weight: bold;
            cursor: pointer;
        }

        .submit-btn:hover {
            background: #084f3b;
        }

        .back-link {
            display: inline-block;
            margin-top: 20px;
            color: #0b6b4f;
            text-decoration: none;
            font-weight: bold;
        }

        .required {
            color: red;
        }

        footer {
            text-align: center;
            background: #12352c;
            color: white;
            padding: 20px;
            margin-top: 40px;
            font-size: 14px;
        }

        @media (max-width: 600px) {
            .registration-card {
                padding: 20px;
            }

            header h1 {
                font-size: 22px;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>DIGITAL GROWTH ACADEMY</h1>
    <p>Learn • Practice • Create • Promote • Grow</p>
</header>

<div class="container">

    <div class="registration-card">

        <h2>Student Registration</h2>

        <p class="intro">
            Welcome to Digital Growth Academy. Complete this form to begin your
            journey in our Beginner Digital Skills Course.
        </p>

        <form>

            <h3 class="section-title">1. Personal Information</h3>

            <label for="fullname">
                Full Name <span class="required">*</span>
            </label>
            <input type="text" id="fullname" name="fullname"
                   placeholder="Enter your full name" required>

            <label for="preferredname">
                Preferred Name
            </label>
            <input type="text" id="preferredname" name="preferredname"
                   placeholder="What should we call you?">

            <label for="email">
                Email Address <span class="required">*</span>
            </label>
            <input type="email" id="email" name="email"
                   placeholder="example@email.com" required>

            <label for="whatsapp">
                WhatsApp Number <span class="required">*</span>
            </label>
            <input type="tel" id="whatsapp" name="whatsapp"
                   placeholder="Enter your WhatsApp number" required>

            <label for="country">
                Country <span class="required">*</span>
            </label>
            <input type="text" id="country" name="country"
                   placeholder="Enter your country" required>


            <h3 class="section-title">2. Course Information</h3>

            <label for="course">
                Select Course
            </label>

            <select id="course" name="course">
                <option value="beginner-digital-skills">
                    Beginner Digital Skills Course
                </option>
            </select>

            <label for="learning">
                Learning Preference
            </label>

            <select id="learning" name="learning">
                <option value="">Select an option</option>
                <option value="self-paced">Self-Paced</option>
                <option value="mentor-support">
                    Self-Paced + Mentor Support
                </option>
            </select>


            <h3 class="section-title">3. Your Digital Experience</h3>

            <label for="level">
                Current Skill Level
            </label>

            <select id="level" name="level">
                <option value="">Select your level</option>
                <option value="complete-beginner">
                    Complete Beginner
                </option>
                <option value="beginner">
                    Beginner
                </option>
                <option value="intermediate">
                    Intermediate
                </option>
            </select>

            <label for="device">
                Main Device You Use
            </label>

            <select id="device" name="device">
                <option value="">Select your device</option>
                <option value="android">Android Phone</option>
                <option value="iphone">iPhone</option>
                <option value="tablet">Tablet</option>
                <option value="laptop">Laptop</option>
                <option value="desktop">Desktop Computer</option>
            </select>

            <label for="internet">
                How often do you have internet access?
            </label>

            <select id="internet" name="internet">
                <option value="">Select an option</option>
                <option value="daily">Daily</option>
                <option value="often">Several times a week</option>
                <option value="sometimes">Sometimes</option>
            </select>


            <h3 class="section-title">4. Your Learning Goals</h3>

            <p>
                What would you like to achieve? Select all that apply.
            </p>

            <div class="checkbox-group">

                <div class="checkbox-item">
                    <input type="checkbox" id="goal1" name="goals"
                           value="digital-skills">
                    <label for="goal1">Learn digital skills</label>
                </div>

                <div class="checkbox-item">
                    <input type="checkbox" id="goal2" name="goals"
                           value="freelancing">
                    <label for="goal2">Start freelancing</label>
                </div>

                <div class="checkbox-item">
                    <input type="checkbox" id="goal3" name="goals"
                           value="clients">
                    <label for="goal3">Find online clients</label>
                </div>

                <div class="checkbox-item">
                    <input type="checkbox" id="goal4" name="goals"
                           value="business">
                    <label for="goal4">Start an online business</label>
                </div>

                <div class="checkbox-item">
                    <input type="checkbox" id="goal5" name="goals"
                           value="content">
                    <label for="goal5">Become a content creator</label>
                </div>

                <div class="checkbox-item">
                    <input type="checkbox" id="goal6" name="goals"
                           value="marketing">
                    <label for="goal6">Learn digital marketing</label>
                </div>

                <div class="checkbox-item">
                    <input type="checkbox" id="goal7" name="goals"
                           value="existing-business">
                    <label for="goal7">Promote my existing business</label>
                </div>

                <div class="checkbox-item">
                    <input type="checkbox" id="goal8" name="goals"
                           value="career">
                    <label for="goal8">Improve my career opportunities</label>
                </div>

            </div>

            <label for="main-goal">
                Tell us about your main goal
            </label>

            <textarea id="main-goal" name="main-goal"
                      placeholder="What do you hope to achieve after completing this course?"></textarea>


            <h3 class="section-title">5. Student Agreement</h3>

            <div class="agreement">

                <div class="checkbox-item">
                    <input type="checkbox" id="agree1" required>
                    <label for="agree1">
                        I confirm that the information I provide is accurate.
                    </label>
                </div>

                <div class="checkbox-item">
                    <input type="checkbox" id="agree2" required>
                    <label for="agree2">
                        I understand that the course does not guarantee
                        employment, clients, or income.
                    </label>
                </div>

                <div class="checkbox-item">
                    <input type="checkbox" id="agree3" required>
                    <label for="agree3">
                        I agree to follow the academy's learning rules and
                        code of conduct.
                    </label>
                </div>

                <div class="checkbox-item">
                    <input type="checkbox" id="agree4" required>
                    <label for="agree4">
                        I understand that a certificate is issued only after
                        completing the required course and assessment requirements.
                    </label>
                </div>

            </div>

            <button type="submit" class="submit-btn">
                Submit Registration
            </button>

        </form>

        <a href="index.html" class="back-link">
            ← Back to Digital Growth Academy
        </a>

    </div>

</div>

<footer>
    <p>© 2026 Digital Growth Academy. All Rights Reserved.</p>
    <p>Learn • Practice • Create • Promote • Grow</p>
</footer>

</body>
</html>
