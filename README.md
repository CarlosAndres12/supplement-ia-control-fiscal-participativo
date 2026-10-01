# Supplementary material: LLM-assisted qualitative analysis of participatory fiscal oversight interviews

Supplementary material for a manuscript on LLM-assisted qualitative content analysis of interviews about
participatory fiscal oversight (control fiscal participativo) in Colombia. The files are the four annexes of
the manuscript, extracted verbatim and kept in Spanish, the language in which they were used.

| File | Content |
|---|---|
| `prompts/01_plan_de_analisis.md` | Analysis plan: categories, subcategories and the five analysis steps |
| `prompts/02_prompt_de_analisis.md` | Markdown analysis prompt run on each interview transcription |
| `prompts/03_prompt_de_resumen.md` | Markdown summary prompt (eight-paragraph analytical text) |
| `prompts/04_conversion_pandoc.txt` | Pandoc command used to convert the Markdown output to Word |

## Notes

- `<<TEXTO ENTREVISTA>>` in the analysis prompt is a placeholder for the transcription of one interview.
- No interview data, transcriptions or model outputs are included: the material is confidential and comes
  from participants in vulnerable conditions.
- In the study the prompts were run locally with a Qwen 2.5 7B instruct model served by Ollama.

## License

Creative Commons Attribution 4.0 International (CC BY 4.0), see `LICENSE`.
