---
layout: page
title: Course Logistics
permalink: /logistics/
---
## Contact
Please contact us on the staff mailing list with any questions: ee274-aut2223-staff [AT] lists.stanford [DOT] edu, or by
making a private post on ED for registered students.

## Course Staff
- **Kedar Tatwawadi** 
    - Research Scientist at WaveOne, Inc.
    - kedart [AT] stanford [DOT] edu
    - **Office hours:** `Thursdays 6:00-7:00pm, STLC 118`
- **Shubham Chandak** 
    - Applied Scientist at Amazon Web Services
    - schandak [AT] stanford [DOT] edu
    - **Office hours:** `Tuesdays 6:00-7:00pm, STLC 118`
- **Prof. Tsachy Weissman** 
    - Electrical Engineering, Stanford
    - tsachy [AT] stanford [DOT] edu
    - **Office hours:** `Fridays 1:00-2:00pm, On Zoom`. Link available on pinned [ED](https://edstem.org/us/courses/29704/discussion/1909607) post.
- **Pulkit Tandon**
  - Electrial Engineering, Stanford
  - tpulkit [AT] stanford [DOT] edu
  - **Office hours:** `Wednesdays 11:00am-12:30pm, Packard 106`


## Lectures
- [Link to explore courses](https://explorecourses.stanford.edu/search?view=catalog&filter-coursestatus-Active=on&page=0&catalog=&academicYear=&q=EE274&collapse=)
- **Date & Time:** Biweekly in-person lectures `Tue, Thu 4:30 PM - 5:50 PM`
- **Location**: [STLC 118](http://campus-map.stanford.edu/?srch=STLC+118) (location subject to change)


## Course elements and grading (tentative)
EE 274 is a `3 unit` course - auditing allowed with instructor permission. The graded course elements include:

- `3` assignments with both theoretical and programming components (`20%` each)
  - and a HW 0 to get you started (`5%`)
- Short quizzes (`5%`)
- final project (`30%`)
- [bonus] participation in the course (`5%`)

## Useful Links
- [Stanford Compression Library](https://github.com/kedartatwawadi/stanford_compression_library) (a collection of compression algorithms implemented in Python)
- [Lecture Notes](https://stanforddatacompressionclass.github.io/notes/contents.html) (for the course notes)
- [ED](https://edstem.org/us/courses/29704/discussion/) (for course Q&A, discussions and announcements)
- [Gradescope](https://www.gradescope.com/courses/436519) (for quizzes and assignment submissions)
- [YouTube Playlist for Lecture Recordings](https://www.youtube.com/watch?v=JFVlAIjHo2c&list=PLv_7iO_xlL0Jgc35Pqn7XP5VTQ5krLMOl) (for the course lectures video recordings)
- [IT Forum](https://web.stanford.edu/group/it-forum/talks/) (for talks on various topics related to compression)

## Prerequisites
Basic probability and programming background (EE178, CS106B or equivalent), or instructor’s permission. Background in statistical signal processing (EE278) and in information theory (EE276) may be helpful for appreciating some of the material, but is not assumed and the relevant background will be covered in class. Some of the final projects will be tailored to the students' backgrounds. 

## Textbook
There is no required textbook, lecture notes and slides will be provided as relevant. 
We might provide references to textbooks from time to time for additional reading.

---

## Course Outline (tentative)
**Lossless Compression Basics**
- Introduction to data compression, prefix-free codes
- Construction of generic prefix-free codes, Kraft Inequality
- Information theory basics, fundamental limits on compression
- Huffman coding, practical prefix-free codes
- Arithmetic coding, adaptive arithmetic coding
- Asymmetric Numeral Systems, rANS/tANS compressors

**Universal lossless compression**
- Asymptotic Equipartition theory
- Non-iid data compression, Entropy rate, context-based Arithmetic coder
- Universal lossless compression, Lempel-Ziv (LZ) 77/78 schemes
- Case Study: `GZIP`, how to implement LZ-based schemes in practice

**Lossy Compression fundamentals**
- Introduction to Lossy compression, scalar-quantization
- Rate-Distortion theory, intuition + practical limitations
- Transform coding, Case Study: Speech compression

**Image/Video Compression**
- Case Study: Image compression `JPEG, BPG`
- Machine Learning based image compression
- Video compression, `H264, H265` video standards
- Perceptual Quality metrics for image/video compression

**Special Topics**
(based on interest and time) 
- Succinct data structures, compression of data structures in the RAM
- Burrows-Wheeler transform
- Lossy compression and denoising
- Distributed compression, practical applications
- Compression of neural network models







