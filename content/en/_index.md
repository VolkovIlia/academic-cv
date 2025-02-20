---
# Leave the homepage title empty to use the site title
# This is a landing page in English with improved SEO and clarity, based on your original file.
title: ""
date: 2025-02-13
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography
    content:
      username: admin
      text: ""
      button:
        text: "Resume (RU)"
        url: "uploads/resume.ru.pdf"
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: "stacked-peaks.svg"
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: stats
    content:
      items:
        - statistic: "11"
          description: |
            Articles
        - statistic: "170+"
          description: |
            Citations
        - statistic: "5"
          description: |
            h-Index
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
      spacing:
        padding: [0, 0, 0, 0]

  - block: markdown
    content:
      title: "🔬 Research Interests & Activities"
      subtitle: ""
      text: |-
        I focus on **innovative nanomaterials** and **heterogeneous catalysts** that address pressing challenges in ecology and energy. My work improves the efficiency of **oxidation and hydrogenation reactions**, as well as **methanol steam reforming**, **CO₂ conversion**, and generating **clean energy from hydrogen**.

        ### 1. High-Performance Catalysts for Industrial Sustainability
        - Designing **bimetallic nanoparticles** (FePt, NiCu, Ag/Au) and coatings on **hexagonal boron nitride (h-BN)** to lower reaction temperatures and enhance selectivity for CO oxidation and CO₂ hydrogenation.
        - Collaborating with research institutes to develop advanced catalysts for **greenhouse gas** utilization, including hydrogen-based solutions in energy infrastructures.

        ### 2. Hydrogen Technologies & Clean Energy
        - Exploring materials and methods to **convert hydrogen directly into electricity**. Project “Giredmet” (featured in the media) highlights the potential of such systems for industry and transport.
        - Evaluating catalytic reforming of methanol and combined “hydrogen + steam reforming” setups, crucial for low-carbon energy and fulfilling ESG criteria.

        ### 3. Photocatalysis & Environmental Cleanup
        - Leveraging oxide and boron-nitride nanomaterials for **photodegradation of organic pollutants** and deep oxidation of toxic emissions.
        - Special interest in **oxygen-doped BN (BNOx)**, which boosts light absorption and catalytic activity in both UV and visible wavelengths.

        ### 4. Novel Composite Materials
        - Employing wet-chemistry (polyol) approaches and **Spark Plasma Sintering (SPS)** to create nanostructured composites (Cu, Fe, Ni, Mo, W, etc.).
        - Emphasizing interfacial interactions and enhanced surface energy to stabilize nanoparticles and extend catalyst lifetimes.

        ### 5. Results & Perspectives
        - Achieved a **30–40% reduction in energy demand** for CO oxidation and elevated CO₂ conversion efficiency.
        - New h-BN-based materials for **UV photodetectors** and photocatalytic systems, enabling advanced environmental monitoring and “green” chemistry.
        - **Direct hydrogen-to-electricity** technologies lay the groundwork for the clean energy sector of the future.

        ## Why It Matters — For Business & Academia
        - **Reduce Industrial Carbon Footprint**: Our technologies save resources, align with ESG trends, and enhance competitiveness in manufacturing.
        - **Accelerate the Shift to Clean Energy**: High-performance materials for low-temperature methanol reforming and CO₂ utilization.
        - **Scalable Solutions**: Core methods adapt readily to commercial-scale plants and large-scale production of nanocatalysts.

        This comprehensive approach—from lab synthesis to rigorous testing—enables rapid delivery of **high-tech, eco-friendly** solutions for **automotive, petrochemical, and chemical** industries. I welcome **collaborations**, **industrial partnerships**, and **joint research** to drive the development of **energy-efficient and sustainable** technologies.
    design:
      columns: "1"

  - block: collection
    id: papers
    content:
      title: "Publications"
      text: ""
      filters:
        folders: ["publication"]
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: "Conferences & Talks"
      filters:
        folders: ["event"]
    design:
      view: article-grid
      columns: 1

  # - block: cta-card
  #   content:
  #     title: "👉 Contact Ilya Volkov"
  #     text: |-
  #       R&D Lead in Materials Science & Green Technology
  #     button:
  #       text: "Write me"
  #       url: "mailto:ilia.volkov@outlook.com"
    design:
      card:
        css_class: "bg-primary-700"
        css_style: ""
---
