<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Form 1 - New Client Intake</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Inter:wght@300;400;500;600&display=swap');
:root{--navy:#1a2744;--gold:#c9a84c;--gold-light:#f5e6c0;--cream:#faf8f4;--gray:#6b7280;--border:#e2d9c8;}
*{box-sizing:border-box;margin:0;padding:0;}
body{font-family:'Inter',sans-serif;background:#f0ece4;color:#1a1a1a;padding:30px 20px;}
.page{max-width:680px;margin:0 auto;background:white;border-radius:4px;overflow:hidden;box-shadow:0 4px 24px rgba(0,0,0,.08);}
.hdr{background:var(--navy);padding:28px 40px;display:flex;align-items:center;justify-content:space-between;}
.hdr h2{font-family:'Playfair Display',serif;color:var(--gold);font-size:19px;margin-bottom:2px;}
.hdr p{color:rgba(255,255,255,.6);font-size:10px;letter-spacing:.08em;text-transform:uppercase;}
.badge{background:var(--gold);color:var(--navy);font-weight:700;font-size:10px;letter-spacing:.1em;text-transform:uppercase;padding:6px 14px;border-radius:2px;}
.title-bar{background:var(--gold-light);border-bottom:2px solid var(--gold);padding:14px 40px;display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:8px;}
.title-bar h3{font-family:'Playfair Display',serif;color:var(--navy);font-size:16px;}
.df{font-size:11px;color:var(--gray);display:flex;align-items:center;gap:6px;}
.df span{display:inline-block;width:110px;border-bottom:1px solid #ccc;height:16px;}
.body{padding:30px 40px;}
.sec{font-size:10px;font-weight:600;letter-spacing:.12em;text-transform:uppercase;color:var(--gold);margin-bottom:12px;margin-top:4px;padding-bottom:5px;border-bottom:1px solid var(--gold-light);}
.grid{display:grid;gap:14px;margin-bottom:20px;}
.g2{grid-template-columns:1fr 1fr;}
.g3{grid-template-columns:1fr 1fr 1fr;}
.field{display:flex;flex-direction:column;gap:4px;}
.field label{font-size:10px;font-weight:500;color:var(--gray);text-transform:uppercase;letter-spacing:.06em;}
.line{border-bottom:1.5px solid var(--border);height:28px;width:100%;}
.tall{border:1.5px solid var(--border);height:60px;width:100%;border-radius:3px;margin-top:4px;}
.checks{display:flex;flex-wrap:wrap;gap:8px 18px;margin-bottom:20px;}
.ci{display:flex;align-items:center;gap:7px;font-size:12.5px;color:#333;}
.ci .box{width:15px;height:15px;border:1.5px solid var(--border);border-radius:2px;flex-shrink:0;}
.sig-row{display:grid;grid-template-columns:2fr 1fr;gap:24px;margin-top:24px;padding-top:18px;border-top:1px solid var(--border);}
.sig-field label{font-size:10px;font-weight:600;letter-spacing:.08em;text-transform:uppercase;color:var(--gray);display:block;margin-bottom:22px;}
.sline{border-bottom:1.5px solid var(--navy);height:1px;}
.ftr{background:var(--cream);border-top:1px solid var(--border);padding:11px 40px;display:flex;justify-content:space-between;align-items:center;}
.ftr p{font-size:10px;color:#aaa;}
.nbadge{background:var(--gold-light);border:1px solid var(--gold);border-radius:3px;padding:7px 13px;font-size:10px;color:var(--navy);font-weight:600;letter-spacing:.06em;text-transform:uppercase;}
@media(max-width:600px){.g2,.g3{grid-template-columns:1fr;}.sig-row{grid-template-columns:1fr;}}
@media print{body{background:white;padding:0;}.page{box-shadow:none;}}
</style>
</head>
<body>
<div class="page">
  <div class="hdr"><div><h2>Your Notary Business</h2><p>Professional Notary Signing Agent</p></div><div class="badge">Form 01</div></div>
  <div class="title-bar"><h3>New Client Intake &amp; Contact Form</h3><div class="df">Date: <span></span></div></div>
  <div class="body">
    <div class="sec">Personal Information</div>
    <div class="grid g2">
      <div class="field"><label>First Name</label><div class="line"></div></div>
      <div class="field"><label>Last Name</label><div class="line"></div></div>
      <div class="field"><label>Phone Number</label><div class="line"></div></div>
      <div class="field"><label>Email Address</label><div class="line"></div></div>
      <div class="field"><label>Date of Birth</label><div class="line"></div></div>
      <div class="field"><label>Preferred Contact Method</label><div class="line"></div></div>
    </div>
    <div class="sec">Address</div>
    <div class="grid"><div class="field"><label>Street Address</label><div class="line"></div></div></div>
    <div class="grid g3">
      <div class="field"><label>City</label><div class="line"></div></div>
      <div class="field"><label>State</label><div class="line"></div></div>
      <div class="field"><label>ZIP Code</label><div class="line"></div></div>
    </div>
    <div class="sec">Signing Details</div>
    <div class="grid g2">
      <div class="field"><label>Document Type(s)</label><div class="line"></div></div>
      <div class="field"><label>Requested Date &amp; Time</label><div class="line"></div></div>
      <div class="field"><label>Signing Location</label><div class="line"></div></div>
      <div class="field"><label>Number of Signers</label><div class="line"></div></div>
    </div>
    <div class="sec">How Did You Hear About Us?</div>
    <div class="checks">
      <div class="ci"><div class="box"></div>Google Search</div>
      <div class="ci"><div class="box"></div>Facebook</div>
      <div class="ci"><div class="box"></div>Referral</div>
      <div class="ci"><div class="box"></div>Notary Platform</div>
      <div class="ci"><div class="box"></div>Returning Client</div>
      <div class="ci"><div class="box"></div>Other: <span style="display:inline-block;width:80px;border-bottom:1px solid #ccc;margin-left:4px;"></span></div>
    </div>
    <div class="sec">Additional Notes</div>
    <div class="tall"></div>
    <div class="sig-row">
      <div class="sig-field"><label>Client Signature</label><div class="sline"></div></div>
      <div class="sig-field"><label>Date</label><div class="sline"></div></div>
    </div>
  </div>
  <div class="ftr"><div class="nbadge">Your Name · Notary Public</div><p>Page 1 of 5 · Notary Client Intake Bundle</p></div>
</div>
</body>
</html>
