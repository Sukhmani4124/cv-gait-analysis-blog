# Beginning Our Computer Vision Project: From Ideas to Direction

When we started the Computer Vision Lab, our first task wasn’t coding or building models. It was figuring out what kind of real-world problem could actually be explored using classical computer vision techniques. Instead of rushing into development, our team spent time discussing different domains and understanding what was realistically possible within the scope of the course.

At the beginning, we explored several directions. Some ideas revolved around traffic monitoring and smart surveillance, while others focused on medical imaging. Although these topics sounded exciting, many of them depended heavily on large datasets or deep learning pipelines. Since our goal was to work primarily with classical computer vision methods, we realized that these problems might not be the best fit.

This pushed us to think differently. Rather than looking for something complex just for the sake of complexity, we wanted a problem where motion, patterns, and visual features could be analyzed in a more interpretable way.

---

## Moving Towards Gait Analysis

During our discussions, we came across the concept of analyzing human walking patterns. The idea of studying gait stood out because walking naturally contains motion, rhythm, and measurable changes over time. It also connects well with topics like background subtraction, feature extraction, and temporal analysis that we were learning in class.

In many rehabilitation environments, therapists observe how patients walk to understand balance or recovery progress. However, visual observation alone can be inconsistent, especially when trying to compare multiple walking sessions. This made us wonder whether a simple vision-based system could help describe walking patterns more objectively.

---

## Our Approach

Instead of building a complicated deep learning system, we decided to design a structured pipeline based on classical computer vision.

The project begins with collecting walking videos captured from a stable viewpoint. These videos act as the foundation of the system. From there, the focus shifts to processing frames to make motion easier to analyze. This includes reducing noise, simplifying visual information, and isolating the moving subject from the background.

Once the motion is clear, the next goal is to extract meaningful gait features. Walking is not just a single frame problem; it involves analyzing changes across time. By observing movement patterns across frames, we aim to compute indicators such as walking speed, step frequency, and symmetry in motion.

---

## Why This Direction Made Sense

One of the reasons we chose this problem is that it allows us to apply core computer vision concepts without relying on heavy computation. The emphasis is on understanding motion rather than simply achieving high prediction accuracy.

Working with classical techniques also helps us better understand how visual features are formed and how movement can be translated into measurable information.

---

## Challenges We Anticipate

As we begin building the system, we expect several practical challenges:

- Maintaining consistent camera positioning  
- Handling background variations  
- Detecting subtle differences in walking patterns  
- Ensuring the analysis remains stable across multiple videos  

These challenges are part of the learning process and will guide how we refine the pipeline over time.

---

## What’s Ahead

This blog marks the starting point of our project journey. In the next posts, we will explore the fundamentals of human gait, the design of our computer vision pipeline, and the steps involved in turning raw video into meaningful analysis.

The goal is not only to build a working system but also to understand how classical computer vision can be applied to real movement-based problems.
