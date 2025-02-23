import React from 'react';

const Resume = () => {
  return (
    <div className="bg-gradient-to-r from-blue-500 to-purple-600 min-h-screen p-8 text-white">
      <div className="max-w-4xl mx-auto bg-white text-black rounded-2xl shadow-lg p-8">
        <h1 className="text-4xl font-bold mb-4 text-center text-purple-700">Samreen Arif</h1>
        <p className="text-center text-lg text-gray-700">Present Address: Islamabad, Pakistan | Permanent Address: Gujranwala, Pakistan</p>
        <p className="text-center text-lg text-gray-700">samreenarif501@gmail.com | +923428454930</p>

        <section className="mt-8">
          <h2 className="text-2xl font-bold mb-2 text-purple-700">Profile</h2>
          <p className="text-gray-800">
            Motivated Electrical Engineer with a Master’s in Electrical Engineering, eager to transition into the RTL to GDSII domain. Passionate about learning and applying skills in RTL
            design, synthesis, place-and-route (PR), and timing analysis. Proficient in hardware design, digital circuits, and embedded systems, with a strong foundation in microcontroller
            programming and system optimization.
          </p>
        </section>

        <section className="mt-8">
          <h2 className="text-2xl font-bold mb-2 text-purple-700">Professional Experience</h2>
          <div className="mb-4">
            <h3 className="text-xl font-semibold">Lab Engineer - FAST–NU Islamabad</h3>
            <p className="text-sm text-gray-600">June 2024 – Present | Islamabad, Pakistan</p>
            <ul className="list-disc list-inside text-gray-800">
              <li>Conducted labs in advanced embedded systems, RTL TO GDS(Digital synthesis) flow, and machine learning.</li>
            </ul>
          </div>
          <div className="mb-4">
            <h3 className="text-xl font-semibold">Embedded Design Engineer - FAST-NU Islamabad</h3>
            <p className="text-sm text-gray-600">June 2024 – Present | Islamabad, Pakistan</p>
            <ul className="list-disc list-inside text-gray-800">
              <li>Assisted in the design and development of embedded systems, focusing on performance optimization.</li>
              <li>Conducted testing and troubleshooting of prototypes to ensure high-quality standards.</li>
            </ul>
          </div>
        </section>

        <section className="mt-8">
          <h2 className="text-2xl font-bold mb-2 text-purple-700">Education</h2>
          <ul className="list-disc list-inside text-gray-800">
            <li><strong>MS Electrical Engineering (Control Systems)</strong> | PIEAS, Islamabad, Pakistan | CGPA: 3.6/4.0 | 2021 – 2023</li>
            <li><strong>BSc Electrical Engineering</strong> | UET RCET, Gujranwala, Pakistan | CGPA: 3.14/4.0 | 2017 – 2021</li>
            <li><strong>FSc Pre-Engineering</strong> | Gujranwala Board, Pakistan | Percentage: 91% | 2015 – 2017</li>
            <li><strong>Matriculation (Science)</strong> | Gujranwala Board, Pakistan | Percentage: 86% | 2013 – 2015</li>
          </ul>
        </section>

        <section className="mt-8">
          <h2 className="text-2xl font-bold mb-2 text-purple-700">Skills</h2>
          <ul className="list-disc list-inside text-gray-800">
            <li>RTL to GDS Flow Full Layout</li>
            <li>Verilog, SystemVerilog, UVM</li>
            <li>Python, C++</li>
            <li>Embedded Systems Development</li>
            <li>Problem Solving and Circuit Design</li>
          </ul>
        </section>

        <footer className="mt-8 text-center">
          <p className="text-sm text-gray-600">Designed with ❤️ by Samreen Arif</p>
        </footer>
      </div>
    </div>
  );
};

export default Resume;
