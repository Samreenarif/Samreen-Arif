import { Card, CardContent, CardHeader, CardTitle, CardDescription } from "@/components/ui/card";
import { Button } from "@/components/ui/button";

export default function Resume() {
  return (
    <div className="p-4 grid gap-4 md:grid-cols-2">
      <Card className="col-span-2">
        <CardHeader>
          <CardTitle className="text-2xl font-bold">Samreen Arif</CardTitle>
          <CardDescription>
            Present Address: Islamabad, Pakistan | Permanent Address: Gujranwala, Pakistan
            <br />
            Email: samreenarif501@gmail.com | Phone: +923428454930
          </CardDescription>
        </CardHeader>
      </Card>

      <Card>
        <CardHeader>
          <CardTitle>Profile</CardTitle>
        </CardHeader>
        <CardContent>
          <p>
            Motivated Electrical Engineer with a Master’s in Electrical Engineering, eager to transition
            into the RTL to GDSII domain. Passionate about learning and applying skills in RTL design,
            synthesis, place-and-route (PR), and timing analysis.
          </p>
        </CardContent>
      </Card>

      <Card>
        <CardHeader>
          <CardTitle>Education</CardTitle>
        </CardHeader>
        <CardContent>
          <p>MS Electrical Engineering (Control Systems), PIEAS, Islamabad, Pakistan (2021–2023)</p>
          <p>CGPA: 3.6/4.0</p>
          <p>BSc Electrical Engineering, UET RCET, Gujranwala, Pakistan (2017–2021)</p>
          <p>CGPA: 3.14/4.0</p>
          <p>FSc Pre-Engineering, Gujranwala Board, Pakistan (2015–2017)</p>
          <p>Percentage: 91%</p>
          <p>Matriculation (Science), Gujranwala Board, Pakistan (2013–2015)</p>
          <p>Percentage: 86%</p>
        </CardContent>
      </Card>

      <Card className="col-span-2">
        <CardHeader>
          <CardTitle>Projects</CardTitle>
        </CardHeader>
        <CardContent>
          <ul className="list-disc pl-5">
            <li>Design and Development of a Configurable Memory Block with Write-Enable Control</li>
            <li>Design and Implementation of Multiplexer, Data Driver, and Register</li>
            <li>Design and Implementation of a RISC-V Processor</li>
            <li>UAV Aided Post Disaster Earthquake Management using AI</li>
            <li>Automatic ATM Theft Detection using Computer Vision</li>
          </ul>
        </CardContent>
      </Card>

      <Card className="col-span-2">
        <CardHeader>
          <CardTitle>Skills</CardTitle>
        </CardHeader>
        <CardContent>
          <p><strong>Computational:</strong> RTL to GDSII Flow, Verilog, SystemVerilog, UVM, Python, C++, Circuit Design, Embedded Systems</p>
          <p><strong>Problem Solving:</strong> Solutions for embedded systems, real-time processing, data acquisition</p>
          <p><strong>Typesetting:</strong> LaTeX</p>
          <p><strong>Languages:</strong> English (Very good), Urdu (Fluent), Punjabi (Fluent)</p>
        </CardContent>
      </Card>

      <Card className="col-span-2 text-center">
        <Button className="mt-4" variant="default">Contact Me</Button>
      </Card>
    </div>
  );
}
