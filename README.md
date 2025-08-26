<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            color: #333;
            line-height: 1.6;
            padding-bottom: 60px;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header {
            background: linear-gradient(to right, #2c3e50, #4ca1af);
            color: white;
            padding: 30px 0;
            text-align: center;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 5px solid rgba(255, 255, 255, 0.3);
            margin: 0 auto 20px;
            background: #ecf0f1;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 60px;
            color: #2c3e50;
        }

        nav {
            background-color: #2c3e50;
            padding: 15px 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-weight: 500;
            font-size: 18px;
            transition: all 0.3s ease;
            padding: 8px 16px;
            border-radius: 4px;
        }

        nav a:hover {
            background-color: rgba(255, 255, 255, 0.1);
            transform: translateY(-2px);
        }

        section {
            background-color: white;
            margin: 30px auto;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
            transition: transform 0.3s ease;
        }

        section:hover {
            transform: translateY(-5px);
        }

        h2 {
            margin-bottom: 20px;
            color: #2c3e50;
            padding-bottom: 10px;
            border-bottom: 3px solid #4ca1af;
            font-size: 28px;
        }

        h3 {
            margin-top: 20px;
            color: #3498db;
            font-size: 22px;
        }

        p {
            margin-bottom: 15px;
            font-size: 18px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
        }

        th, td {
            border: 1px solid #ddd;
            padding: 15px;
            text-align: center;
        }

        th {
            background: linear-gradient(to bottom, #4ca1af, #2c3e50);
            color: white;
            font-weight: 600;
            font-size: 18px;
        }

        tr:nth-child(even) {
            background-color: #f9f9f9;
        }

        tr:hover {
            background-color: #f1f1f1;
        }

        tfoot {
            font-weight: bold;
            background-color: #e8f4fc;
        }

        .academic-highlights {
            display: flex;
            justify-content: space-between;
            margin-top: 30px;
            flex-wrap: wrap;
        }

        .highlight-card {
            flex-basis: 30%;
            background: linear-gradient(135deg, #4ca1af 0%, #2c3e50 100%);
            color: white;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            margin-bottom: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .highlight-card h3 {
            color: white;
            margin-top: 0;
            font-size: 24px;
        }

        .percentage {
            font-size: 32px;
            font-weight: bold;
            margin: 10px 0;
        }

        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 50px;
            font-size: 16px;
        }

        @media (max-width: 768px) {
            nav a {
                display: block;
                margin: 10px 0;
            }
            
            .academic-highlights {
                flex-direction: column;
            }
            
            .highlight-card {
                flex-basis: 100%;
                margin-bottom: 15px;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <div class="profile-img">NK</div>
            <h1>NISHANT KUMAR SINGH</h1>
            <p>Computer Science Student</p>
        </div>
    </header>

    <nav>
        <div class="container">
            <a href="#about">About</a>
            <a href="#education">Education</a>
            <a href="#class10">Class 10</a>
            <a href="#class12">Class 12</a>
        </div>
    </nav>

    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>I am a third-year Computer Science student at AKS University with a passion for programming, software development, and emerging technologies. I enjoy solving complex problems and continuously expanding my knowledge in the field of computer science.</p>
            <p>My academic journey has been marked by consistent performance and dedication to learning. I believe in the power of technology to transform lives and am excited to contribute to this field in the future.</p>
        </section>

        <section id="education">
            <h2>Education</h2>
            
            <h3>Bachelor of Computer Science</h3>
            <p><strong>AKS University</strong> | 2023 - Present</p>
            <p>Current CGPA: 8.7/10</p>
            
            <h3>Class 12 (CBSE Board)</h3>
            <p><strong>Gyanasthali Public School</strong> | 2020 - 2022</p>
            <p>Percentage: 80.4%</p>
            
            <h3>Class 10 (CBSE Board)</h3>
            <p><strong>Gyanasthali Public School</strong> | 2019 - 2020</p>
            <p>Percentage: 82.2%</p>

            <div class="academic-highlights">
                <div class="highlight-card">
                    <h3>Class 10</h3>
                    <div class="percentage">82.2%</div>
                    <p>CBSE Board</p>
                </div>
                <div class="highlight-card">
                    <h3>Class 12</h3>
                    <div class="percentage">80.4%</div>
                    <p>CBSE Board</p>
                </div>
                <div class="highlight-card">
                    <h3>University</h3>
                    <div class="percentage">8.7 CGPA</div>
                    <p>Current Score</p>
                </div>
            </div>
        </section>

        <section id="class10">
            <h2>Class 10 Marksheet (CBSE)</h2>
            <table>
                <thead>
                    <tr>
                        <th>Subject</th>
                        <th>Marks Obtained</th>
                        <th>Maximum Marks</th>
                        <th>Grade</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>English</td>
                        <td>82</td>
                        <td>100</td>
                        <td>A2</td>
                    </tr>
                    <tr>
                        <td>Hindi</td>
                        <td>85</td>
                        <td>100</td>
                        <td>A2</td>
                    </tr>
                    <tr>
                        <td>Mathematics</td>
                        <td>80</td>
                        <td>100</td>
                        <td>B1</td>
                    </tr>
                    <tr>
                        <td>Science</td>
                        <td>83</td>
                        <td>100</td>
                        <td>A2</td>
                    </tr>
                    <tr>
                        <td>Social Science</td>
                        <td>81</td>
                        <td>100</td>
                        <td>A2</td>
                    </tr>
                </tbody>
                <tfoot>
                    <tr>
                        <td><strong>Total</strong></td>
                        <td><strong>411</strong></td>
                        <td><strong>500</strong></td>
                        <td><strong>82.2%</strong></td>
                    </tr>
                </tfoot>
            </table>
        </section>

        <section id="class12">
            <h2>Class 12 Marksheet (CBSE)</h2>
            <table>
                <thead>
                    <tr>
                        <th>Subject</th>
                        <th>Marks Obtained</th>
                        <th>Maximum Marks</th>
                        <th>Percentage</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>English Core</td>
                        <td>82</td>
                        <td>100</td>
                        <td>82%</td>
                    </tr>
                    <tr>
                        <td>Physics</td>
                        <td>79</td>
                        <td>100</td>
                        <td>79%</td>
                    </tr>
                    <tr>
                        <td>Chemistry</td>
                        <td>81</td>
                        <td>100</td>
                        <td>81%</td>
                    </tr>
                    <tr>
                        <td>Mathematics</td>
                        <td>78</td>
                        <td>100</td>
                        <td>78%</td>
                    </tr>
                    <tr>
                        <td>Computer Science</td>
                        <td>85</td>
                        <td>100</td>
                        <td>85%</td>
                    </tr>
                    <tr>
                        <td>Physical Education</td>
                        <td>78</td>
                        <td>100</td>
                        <td>78%</td>
                    </tr>
                </tbody>
                <tfoot>
                    <tr>
                        <td><strong>Total</strong></td>
                        <td><strong>483</strong></td>
                        <td><strong>600</strong></td>
                        <td><strong>80.4%</strong></td>
                    </tr>
                </tfoot>
            </table>
        </section>
    </div>


</body>
</html>
