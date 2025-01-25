import React from "react";

export default function ResumeWebsite() {
  return (
    <div className="min-h-screen bg-gray-100 flex flex-col items-center p-6">
      <header className="bg-white shadow w-full p-6 rounded-2xl mb-6">
        <h1 className="text-3xl font-bold text-center">Jamanla Suresh</h1>
        <p className="text-center text-gray-600">Data Analyst | AI Enthusiast | Problem Solver</p>
      </header>

      <main className="max-w-4xl w-full bg-white p-6 rounded-2xl shadow">
        {/* Objective Section */}
        <section className="mb-6">
          <h2 className="text-2xl font-semibold mb-3">Objective</h2>
          <p className="text-gray-700">
            To obtain a challenging Data Analyst position in a dynamic and innovative organization where I can use my technical and analytical skills.
          </p>
        </section>

        {/* Experience Section */}
        <section className="mb-6">
          <h2 className="text-2xl font-semibold mb-3">Professional Experience</h2>
          <ul className="space-y-4">
            <li>
              <h3 className="text-xl font-medium">Artificial Intelligence Intern</h3>
              <p className="text-gray-600">Aicte (Matlab) | Online | Apr 2023 - Jul 2023</p>
              <p className="text-gray-700">
                Collaborated with teams to align AI outputs with business goals, documented workflows, and built optimized machine learning models using Python and TensorFlow.
              </p>
            </li>
            <li>
              <h3 className="text-xl font-medium">Artificial Intelligence Intern</h3>
              <p className="text-gray-600">Wayspire | Online | May 2024 - Jul 2024</p>
              <p className="text-gray-700">
                Worked on data analysis, NLP tasks like sentiment analysis and text classification, and utilized AI/ML libraries such as Scikit-learn, Pandas, and NLTK.
              </p>
            </li>
            <li>
              <h3 className="text-xl font-medium">Data Analyst Intern</h3>
              <p className="text-gray-600">[Company Name] | [Location] | [Dates]</p>
              <p className="text-gray-700">
                Processed and cleaned raw data using Excel and SQL, created interactive dashboards in Power BI, and collaborated on data visualization practices.
              </p>
            </li>
            <li>
              <h3 className="text-xl font-medium">Junior Data Analyst</h3>
              <p className="text-gray-600">[Company Name] | [Location] | [Dates]</p>
              <p className="text-gray-700">
                Assisted in transforming large datasets, designed Excel-based dashboards, and presented findings to stakeholders for data-driven decisions.
              </p>
            </li>
          </ul>
        </section>

        {/* Education Section */}
        <section className="mb-6">
          <h2 className="text-2xl font-semibold mb-3">Education</h2>
          <ul className="list-disc list-inside text-gray-700">
            <li>Teegala Krishna Reddy Engineering College (2025) - Major: Artificial Intelligence, Minor: Machine Learning</li>
            <li>Sri Krishnadevaraya Govt Polytechnic College (2021) - Major: Mechanical Engineering</li>
            <li>Jharkhand State Open School (2020) - Major: Mathematics, Minor: Computer Science</li>
          </ul>
        </section>

        {/* Skills Section */}
        <section className="mb-6">
          <h2 className="text-2xl font-semibold mb-3">Technical Proficiency</h2>
          <ul className="list-disc list-inside text-gray-700">
            <li>Programming Languages: Python, R, SQL</li>
            <li>Data Visualization: Tableau, Power BI, Matplotlib, Seaborn</li>
            <li>Databases: MySQL, MongoDB</li>
            <li>Data Analysis Techniques: Data cleaning, preprocessing, trend analysis</li>
          </ul>
        </section>

        {/* Skills & Abilities Section */}
        <section className="mb-6">
          <h2 className="text-2xl font-semibold mb-3">Skills & Abilities</h2>
          <ul className="list-disc list-inside text-gray-700">
            <li>Management</li>
            <li>Problem Solving</li>
            <li>Communication</li>
            <li>Leadership</li>
          </ul>
        </section>

        {/* Contact Section */}
        <section>
          <h2 className="text-2xl font-semibold mb-3">Contact</h2>
          <p className="text-gray-700">Email: sjamanla357@gmail.com</p>
          <p className="text-gray-700">Phone: 8332040380</p>
          <p className="text-gray-700">GitHub: github.com/jamanla</p>
        </section>
      </main>

      <footer className="mt-6 text-gray-600 text-sm">
        © {new Date().getFullYear()} Jamanla Suresh. All rights reserved.
      </footer>
    </div>
  );
}
