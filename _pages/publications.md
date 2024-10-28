---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

You can find my articles on [my Google Scholar profile](https://scholar.google.co.uk/citations?hl=en&user=Dr5nIRYAAAAJ), too.

[7] **Amirhossein Sojoodi**, Yiltan Hassan Temucin, Ahmad Afsahi , "Enhancing Intra-Node GPU-to-GPU Performance in MPI + UCX through Multi-Path Communication", Proceedings of the International Workshop on Extreme Heterogeneity Solutions (ExHET), pp. 1-6, DOI: [10.1145/3642961.3643800](https://doi.org/10.1145/3642961.3643800) - <span style="color:red">Best Paper Award</span>.

[6] Pedram Alizadeh, **Amirhossein Sojoodi**, Yiltan Hassan Temucin, Ahmad Afsahi , "Efficient Process Arrival Pattern Aware Collective Communication for Deep Learning", Proceedings of the European MPI Users' Group Meeting (EuroMPI), pp. 68-78, DOI: [10.1145/3555819.3555857](https://doi.org/10.1145/3555819.3555857)

[5] Philipp A. Witte, Russell J. Hewett, Kumar Saurabh, **Amirhossein Sojoodi**, Ranveer Chandra , "SciAI4Industry - Solving PDEs for industry-scale problems with deep learning", arXiv (2022), pp. 1-11, DOI: [10.48550/arXiv.2211.12709](https://doi.org/10.48550/arXiv.2211.12709)

[4] Yiltan Hassan Temucin, **Amirhossein Sojoodi**, Pedram Alizadeh, Ahmad Afsahi , "Efficient Multi-Path NVLink / PCIe-Aware UCX based Collective Communication for Deep Learning", Proceedings of the IEEE Symposium on High-Performance Interconnects (HOTI), pp. 1-10, DOI: [10.1109/HOTI52880.2021.00018](https://doi.org/10.1109/HOTI52880.2021.00018)

[3] Yiltan Hassan Temucin, **Amirhossein Sojoodi**, Pedram Alizadeh, Benjamin W Kitor, Ahmad Afsahi , "Accelerating Deep Learning using Interconnect-Aware UCX Communication for MPI Collectives", IEEE Micro (2021), pp. 1-9, DOI: [10.1109/MM.2022.3148670](https://doi.org/10.1109/MM.2022.3148670)

[2] Majid Salimi Beni, **Amirhossein Sojoodi**, Farshad Khunjush , "A GPU-Enabled Extension for Apache Ignite to Facilitate Running Genetic Algorithms", Proceedings of the International Symposium on Computer Architecture and Digital Systems (CADS), pp. 1-8, DOI: [10.1109/CADS50570.2020.9211857](https://doi.org/10.1109/CADS50570.2020.9211857)

[1] **Amirhossein Sojoodi**, Majid Salimi Beni, Farshad Khunjush , "Ignite-GPU: a GPU-enabled in-memory computing architecture on clusters", Journal of Supercomputing (2020), pp. 1-28, DOI: [10.1007/s11227-020-03390-z](https://doi.org/10.1007/s11227-020-03390-z)

<!-- New style rendering if publication categories are defined -->
<!-- {% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h4>{{ category[1].title }}</h4><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %} -->
