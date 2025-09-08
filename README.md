<style>
  .pagehead h1 {
    display: none;
  }
</style>

<table style="width:100%;border:0;" border="0">
  <tr>
    <!-- Left column: Bio -->
    <td style="vertical-align:middle;border:0;">
      <p>
        I’m a junior at <strong>Georgia Tech (’27)</strong>
        <img src="/gt-mark.svg" alt="Georgia Tech logo"
             style="height:1em;width:auto;vertical-align:-0.2em;margin-left:4px;">
        working on projects at the intersection of AI, robotics, and human-computer interaction.  
        My interests include autonomous systems, decision-making, computer vision + SLAM and perception, and building software that makes an impact.
        I'm also a founder of a <a href="https://hamsa.ngo" target="_blank" rel="noopener noreferrer">nonprofit</a>.
      </p>
      <p>
        <a href="mailto:shasnain9@gatech.edu">Feel free to contact me if you'd like to collaborate on research or nonprofit initiatives.</a>
      </p>
    </td>

    <!-- Right column: Photo -->
    <td style="width:220px;text-align:right;border:0;">
      <img src="me.jpg" alt="Ali Hasnain" style="width:200px;height:200px;border-radius:50%;object-fit:cover;">
    </td>
  </tr>
</table>

---

## Research

**JetAuto Autonomous Navigation at Clarkson University:**

As a Visiting Researcher at Clarkson University, I lead a project team of undergraduate and master’s students developing methods for autonomous navigation on a Jetson Nano robot.

Using **neural networks, ROS, and OpenCV**, we are building perception, control, and vision pipelines that enable the robot to navigate environments autonomously.  

I report directly to
<!-- Chuck Thorpe -->
<a class="hover-card" href="https://www.clarkson.edu/people/chuck-thorpe" target="_blank" rel="noopener noreferrer">
  <span class="hc-trigger"><strong>Chuck Thorpe</strong></span>
  <span class="hc-pop" role="tooltip" aria-label="Photo of Chuck Thorpe">
    <img src="/images/mentors/chuck.jpg" alt="Chuck Thorpe headshot">
    <span class="hc-name">Chuck Thorpe</span>
    <span class="hc-title">Professor · Robotics · Clarkson University</span>
  </span>
</a>
a pioneer in robotics, who serves as my mentor on this research.

**Decision Processes Lab at Georgia Tech:**  

At Georgia Tech, I conduct research in the
<a href="https://dpl.gatech.edu/" target="_blank" rel="noopener noreferrer"><strong>Decision Processes Lab</strong></a>,
reporting directly to
<!-- Rick Thomas -->
<a class="hover-card" href="https://psychology.gatech.edu/people/rick-thomas" target="_blank" rel="noopener noreferrer">
  <span class="hc-trigger"><strong>Rick Thomas</strong></span>
  <span class="hc-pop" role="tooltip" aria-label="Photo of Rick Thomas">
    <img src="/images/mentors/rick.jpg" alt="Rick Thomas headshot">
    <span class="hc-name">Rick Thomas.</span>
    <span class="hc-title">PI · Decision Processes Lab · Georgia Tech</span>
  </span>
</a>
I contribute to the <strong>HyGENE</strong> model of hypothesis generation: turning cognitive theory into working code and experiments. My work includes implementing model components, running simulation/parameter sweeps, evaluating fit to human data, and building clean analysis/visualization pipelines to make the model easier to test and extend.

---

## Projects

- [**GT Movies Store**](gt-movies.md)  
  A Django 5 web application built as part of CS 2340 coursework, featuring a movie catalog with search, add/edit functionality, and user authentication.

<style>
  /* Hover-card */
  .hover-card{ position:relative; display:inline-block; }
  .hover-card .hc-trigger{ text-decoration:underline; text-underline-offset:2px; }

  /* Popup */
  .hover-card .hc-pop{
    position:absolute; left:50%; bottom:1.6em;
    transform:translate(-50%, 6px) scale(.96);
    opacity:0; pointer-events:none; z-index:30;

    background:#fff; color:#111; /* ensure normal text color inside pop */
    border:1px solid #e5e7eb; border-radius:12px;
    box-shadow:0 8px 24px rgba(0,0,0,.18);
    padding:8px; width:180px;
    transition:opacity .18s ease, transform .18s ease;
    white-space:normal; word-wrap:break-word;
  }

  .hover-card .hc-pop img{
    display:block; width:100%; height:auto; border-radius:8px;
  }

  /* Make inline elements stack as blocks */
  .hover-card .hc-name, .hover-card .hc-title{ display:block; }
  .hover-card .hc-name{
    font:600 14px/1.2 system-ui, -apple-system, Segoe UI, Roboto, Inter, Arial;
    margin-top:6px;
  }
  .hover-card .hc-title{
    color:#6b7280;
    font:12px/1.2 system-ui, -apple-system, Segoe UI, Roboto, Inter, Arial;
  }

  /* little arrow */
  .hover-card .hc-pop::after{
    content:""; position:absolute; top:100%; left:50%; transform:translateX(-50%);
    border-width:6px 6px 0 6px; border-style:solid;
    border-color:#fff transparent transparent transparent;
    filter: drop-shadow(0 2px 2px rgba(0,0,0,.06));
  }

  /* show on hover or keyboard focus */
  .hover-card:hover .hc-pop,
  .hover-card:focus-within .hc-pop{
    opacity:1; transform:translate(-50%, 0) scale(1);
  }

  @media (prefers-reduced-motion: reduce){
    .hover-card .hc-pop{ transition:none; }
  }
</style>

