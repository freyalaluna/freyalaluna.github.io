---
draft: false
jobTitle: Mozilla Open-Source Intern
company: Outreachy
location: 'Fort Collins, CO'
duration: Nov. 2023 - Mar. 2024
title: Mozilla Open-Source Intern
date: 2025-01-01T07:00:00.000Z
---

### My first job as a software developer

After I graduated in the Spring of 2023, I was recommended to apply to a program called [Outreachy](https://www.outreachy.org/) by one of my peers. The program seeks to give burgeoning developers from marginalized backgrounds a chance to get experience through the realm of Open-Source Software. After several months of working on my application and contributing to the Firefox backend, I was chosen as one of five interns to work at Mozilla under the direct guidance of two Principle developers there.

During my 3-month internship, I was tasked with bringing the Firefox browser's [Reporting API](https://developer.mozilla.org/en-US/docs/Web/API/Reporting_API) up to [modern standards](https://www.w3.org/TR/CSP3/), as it had gone without maintenance for several years. This was incredibly daunting at first! The codebases I had worked with during my undergraduate program were nowhere near the scope of what I was working with at Mozilla. It took a lot of hours of pouring over documentation, debugging, and asking many, many questions to my mentors and the Firefox open-source community to start getting a grasp of everything I was working with. Finally getting to that point felt incredibly rewarding, though.

My work primarily focused on implementing an updated way to handle the reception of policy violations, creation of reports from said violation, report delivery, and parsing endpoints for use with the reports in C++. During this process, I also optimized how reports were being sent to the processing queue, cutting down on the time taken before a report was sent. This also involved creating rigorous tests for each step of the process, including mocking API calls. Additionally, I interfaced with tests on the Javascript frontend to ensure that all violations were being properly identified and routed, and reports were being properly constructed and sent back to their frontend endpoints after construction. You can read about my contributions [here](https://phabricator.services.mozilla.com/D197480)!
