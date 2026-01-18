# Living Signal: An Academic-Practitioner Framework for Journaling, Signal Encoding, and Persona Development

Author: Aaron Sahlstrom  
Date: 1/5/2026

## Abstract

This paper presents Living Signal, a human-first journaling methodology designed to improve large language model (LLM) retrieval quality, semantic coherence, and persona development. Living Signal introduces lightweight signal annotations embedded in narrative journaling to preserve authorial intent, emotional salience, and identity continuity across time. We situate the methodology within existing research on expressive writing, sensemaking, reflective practice, and personal informatics, and demonstrate how signal-aware retrieval enables the construction of interpretive, relational AI personas rather than archival or transactional agents.

## 1. Introduction

Personal journaling has long served as a tool for reflection, emotional processing, and identity construction. With the advent of LLMs capable of long-horizon reasoning and retrieval-augmented generation (RAG), personal journals are increasingly being revisited as data sources for memory, self-modeling, and digital legacy. However, traditional journaling practices lack structures that preserve authorial intent and contextual salience for machine interpretation. Living Signal addresses this gap by introducing minimal, human-legible signal annotations that guide LLM retrieval and persona behavior without imposing rigid schemas.

## 2. Background and Related Work

The Bullet Journal method (Carroll, 2018) emphasizes rapid logging and flexible structure. Expressive writing research (Pennebaker & Chung, 2011) demonstrates psychological benefits of narrative reflection. Sensemaking theory (Weick, 1995) frames meaning as retrospective and socially constructed, while Schon's reflective practitioner model (1983) highlights reflection-in-action. Personal informatics systems (Li et al., 2010) explore self-tracking but often privilege quantitative data. Living Signal synthesizes these traditions while addressing the requirements of LLM-based retrieval systems.

## 3. The Living Signal Methodology

Living Signal uses context-first narrative entries augmented by optional signal blocks. A signal block consists of a standardized prefix (for example, "Signal: Reflection") followed by free-form prose. Signals are intentionally sparse and human-authored, avoiding tags or taxonomies that disrupt natural writing. The canonical signal set includes Reflection, Emotion, Decision, Question, Memory, and Identity.

## 4. Signals as Authorial Intent Encoding

Signals function as intent annotations that explicitly mark how the author understands a portion of text. Unlike tags, signals do not categorize content but indicate interpretive stance. This distinction allows downstream systems to weight meaning, affect, and self-concept differently during retrieval. Signals act as semantic anchors across time, enabling longitudinal coherence.

## 5. Persona Development via Signal-Aware Retrieval

In a signal-aware RAG pipeline, journal entries are chunked with signal context preserved. Retrieval prioritizes signal-aligned passages when responding to user queries. For example, Emotion signals bias persona tone toward empathy, while Reflection signals encourage synthesis and perspective-taking. Over time, recurrent signal patterns shape a persona's conversational posture, values emphasis, and interpretive depth.

## 6. Example Trace

A daily entry marked with "Signal: Emotion" describing grief will be retrieved preferentially when the persona is asked about loss. The persona responds not by summarizing events, but by mirroring emotional language and acknowledging continuity of feeling. This behavior differs materially from retrieval based solely on keyword similarity.

## 7. Design Goals and Constraints

Living Signal prioritizes human usability, minimal cognitive load, and future-proof interpretability. The method intentionally avoids exhaustive metadata, probabilistic labeling, or automated sentiment extraction. Signals are optional, contextual, and author-controlled.

## 8. Ethical Considerations

Persona systems derived from personal journals raise ethical questions around consent, interpretive authority, and posthumous representation. Living Signal mitigates risks by preserving author voice and intent, while acknowledging that any persona is a partial, situated construct.

## 9. Limitations and Future Work

This framework has not yet been validated through large-scale longitudinal studies. Future work includes empirical evaluation of retrieval accuracy, persona alignment metrics, and cross-user generalizability.

## 10. Conclusion

Living Signal offers a pragmatic bridge between human reflective practices and machine interpretation. By embedding minimal signals within narrative journaling, it enables the construction of AI personas that are meaning-aware, emotionally grounded, and longitudinally coherent.

## References

- Carroll, R. (2018). *The Bullet Journal Method.*
- Pennebaker, J. W., and Chung, C. K. (2011). Expressive writing and its links to mental and physical health.
- Weick, K. E. (1995). *Sensemaking in Organizations.*
- Schon, D. A. (1983). *The Reflective Practitioner.*
- Li, I., Dey, A., and Forlizzi, J. (2010). A stage-based model of personal informatics systems.

---
**Living Signal™** © 2026 Aaron Sahlstrom. Licensed under [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/).
