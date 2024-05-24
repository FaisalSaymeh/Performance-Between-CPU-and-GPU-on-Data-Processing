# Performance Analysis Between CPU and GPU for Machine Learning

## Introduction

In the realm of machine learning, the selection of appropriate hardware plays a pivotal role in attaining peak performance and efficiency. Among the primary computing devices utilized for machine learning tasks, GPUs and CPUs stand out, each showcasing distinct strengths and weaknesses.

Traditionally, CPUs or central processing units have held the preference owing to their versatility and adeptness in multitasking. CPU acts as the computer’s brain, executing fundamental instructions such as arithmetic, logic operations, and I/O tasks. On the other hand, a GPU, or graphics processing unit, designed originally for 2D and 3D graphics and specialized in rendering for high-resolution graphics, but these days with the surge in big data and machine learning applications has propelled GPUs into the spotlight, given their capacity to manage extensive datasets and execute parallel computations.

This project aims to delve into the variances between GPU and CPU performance by delving into the specifications of the processors, to determine which company and which processors of CPU or GPU provide superior power for machine learning.
About The Dataset

This dataset contains 2,185 CPUs and 2,668 GPUs to understand the development trend of CPUs and GPUs and their performance. It encompasses a diverse set of benchmarks and metrics like process size, thermal design power(TDP), die size, number of transistors, and frequency to evaluate the performance of these two types of processors. In addition, the release date and the manufacturer to see the evolution of these processors’ performance during these years.

## Important Terminology:

  - Process Size (nm): the size of the transistors used in a processor. The size plays a significant role and typically enables a greater number of transistors to be accommodated within the same physical area (Die Area), potentially leading to enhanced performance, decreased power consumption, and reduced production expenses(nm is an acronym for Nano-meter. It is used to measure microscopic objects or devices like transistors found in processors or atomic structures).

  - Die Size (mm^2): In computing, die refers to the piece of silicon of which the processing unit (a GPU or CPU) consists, often called a chip. Die size means the size of the chunk on a silicon wafer that belongs to one chip. Smaller die sizes allow for more transistors to be packed into the same area resulting in higher processing power and also consuming less power. The number and density of transistors packed into the die determine the processor’s computational capacity. (mm^2 is a short form for square millimeters).

  - TDP(W): the electrical energy usage of a computer chip operating at its maximum theoretical load, measured in watts (W).

  - Transistors (million): are minuscule electronic components, that function as switches governing the flow of electricity within a circuit. Within processor architecture, these transistors serve as the foundational elements for constructing logic gates and memory cells, essential components that constitute a processor.

  - Freq (MHz): relates to the clock rate or clock speed at which a processor’s clock generator can produce pulses to perform operations within a specified time frame, which is the responsibility of the billions of transistors within the processor to produce these pulses. For instance, a processor operating at a clock speed of 3.2 GHz (3200 MHz) completes 3.2 billion cycles per second.

