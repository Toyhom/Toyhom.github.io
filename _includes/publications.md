<style>
  .publication-list {
    margin-top: 0.8rem;
  }

  .publication-section {
    margin: 1.45rem 0 1.8rem;
  }

  .publication-section__header {
    align-items: baseline;
    border-bottom: 1px solid #e6e8eb;
    display: flex;
    gap: 0.75rem;
    justify-content: space-between;
    margin-bottom: 0.65rem;
    padding-bottom: 0.35rem;
  }

  .publication-section__title {
    color: #1f2933;
    font-size: 1.03rem;
    font-weight: 700;
    margin: 0;
  }

  .publication-section__count {
    color: #6b7280;
    font-size: 0.82rem;
    white-space: nowrap;
  }

  .publication-card {
    background: #fff;
    border: 1px solid #e7ebef;
    border-left: 4px solid #8bb8d8;
    border-radius: 6px;
    margin: 0.58rem 0;
    padding: 0.75rem 0.9rem;
  }

  .publication-section--featured .publication-card {
    border-left-color: #3f8f72;
  }

  .publication-card__title {
    color: #1f2933;
    font-weight: 700;
    line-height: 1.35;
    margin-bottom: 0.28rem;
  }

  .publication-card__authors {
    color: #47515d;
    font-size: 0.94rem;
    line-height: 1.42;
    margin-bottom: 0.2rem;
  }

  .publication-card__meta {
    align-items: center;
    color: #56616d;
    display: flex;
    flex-wrap: wrap;
    font-size: 0.92rem;
    gap: 0.45rem;
    line-height: 1.35;
  }

  .publication-card__link {
    color: #2f6f9f;
    font-weight: 600;
    text-decoration: none;
  }
</style>

<div class="publication-list">
{% assign representative_publications = site.data.publications | where: "category", "representative" %}
{% assign other_publications = site.data.publications | where: "category", "other" %}
{% assign preprint_publications = site.data.publications | where: "category", "preprint" %}

  <section class="publication-section publication-section--featured">
    <div class="publication-section__header">
      <h3 class="publication-section__title">Selected First-Author Publications</h3>
      <span class="publication-section__count">{{ representative_publications | size }} papers</span>
    </div>
    {% for pub in representative_publications %}
      {% include publication-card.html pub=pub %}
    {% endfor %}
  </section>

  <section class="publication-section">
    <div class="publication-section__header">
      <h3 class="publication-section__title">Other Publications</h3>
      <span class="publication-section__count">{{ other_publications | size }} papers</span>
    </div>
    {% for pub in other_publications %}
      {% include publication-card.html pub=pub %}
    {% endfor %}
  </section>

  <section class="publication-section">
    <div class="publication-section__header">
      <h3 class="publication-section__title">Preprints</h3>
      <span class="publication-section__count">{{ preprint_publications | size }} papers</span>
    </div>
    {% for pub in preprint_publications %}
      {% include publication-card.html pub=pub %}
    {% endfor %}
  </section>
</div>
