---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**Journals:**

[J1] S. Arthi, N. B. Mehta, and C. Singh, “Hybrid access MAC protocol in Wi-Fi: Analysis and optimal resource allocation policy design,” IEEE Trans. Mob. Comput., vol. 25, no. 4, pp. 5742-5757, Apr. 2026.

[J2] S. Arthi and N. B. Mehta, “S. Arthi and N. B. Mehta, "Cross-layer throughput analysis of hybrid-access Wi-Fi in time-Varying channels," IEEE Wireless Commun. Lett., vol. 15, pp. 3676-3680, Jun. 2026.

[J3] S. Arthi and N. B. Mehta, “Multi-link operation modes in Wi-Fi 7 with UORA: Throughput and access delay comparisons,” under review in IEEE Trans. Mobile Comput., 2026.

[J4] S. Arthi and N. B. Mehta, “Simultaneous multi-link operation in Wi-Fi 7 with UORA: Throughput and delay implications with legacy users,” to be submitted to IEEE Trans. Commun., 2026.

**Conferences:**

[C1] S. Arthi and N. B. Mehta, “Saturation throughput analysis of hybrid access MAC protocol in IEEE 802.11ax WLANs,” in Proc. IEEE Glob. Commun. Conf (GLOBECOM), Cape Town, South Africa, Dec. 2024.

[C2] S. Arthi and N. B. Mehta, “Saturation throughput analysis of UORA-enabled multi-Link operation in IEEE 802.11be Wi-Fi,” in Proc. IEEE Int. Conf. Commun. (ICC), Glasgow, UK, May 2026.

[C3] S. Arthi and N. B. Mehta, “Effectiveness of UORA-enabled multi-Link operation in Wi-Fi 7 in the presence of legacy users,” submitted to IEEE Wireless Commun. Netw. Conf. (WCNC), 2027.

[C4] K. Tushar Vikash, S. Arthi, and N. B. Mehta, “Saturation throughput and mean access delay of enhanced multi-link single-radio in Wi-Fi 7,” submitted to IEEE Wireless Commun. Netw. Conf. (WCNC), 2027


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

