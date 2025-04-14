# 41_r01

# Variables del Estudio

## 🔹 Necesarias **SIEMPRE**

### Diagnóstico
- `clinical_diagnosis`: Diagnóstico del paciente.
- `clinical_diagnosis_adsp`: Subtipo de Alzheimer (incluye logopenic PPA).
- `clinical_diagnosis_ftdsp`: Subtipo de Frontotemporal Dementia.
- `diagnosisX` (restantes): Proveen información clave sobre el proceso diagnóstico. Incluye si la persona tiene MCI y su subtipo.

### Demográficas
- `demo_age`: Edad del participante.
- `demo_sex`: Sexo del participante.
- `demo_race`: Raza del participante.
- `demo_language`: Idioma de preferencia del participante.
- `demo_language_num`: Número de idiomas que habla el participante.
- `demo_language_indig`: ¿Habla el participante lenguas indígenas?
- `demo_language_indig_esp`: Lengua indígena hablada.
- `clinical_laterality`: Mano dominante del participante.
- `cog_ed`: Años de escolaridad.

### Clínicas
- `clinical_visual`: ¿Visión normal sin lentes?
- `clinical_audit`: ¿Audición normal sin audífonos?
- `ao`: Edad al momento del diagnóstico.
- `yad`: Año del diagnóstico.

### Cognitivas

#### Screening
- `cdr_memory`, `cdr_orient`, `cdr_prblm`, `cdr_cmnaff`, `cdr_hobby`, `cdr_care`, `cdr_behav`, `cdr-lang`: Puntajes de las subescalas del **CDR**.
- `cdr_boxscore`: Suma de los puntajes del CDR.
- `cdr_cdrtot`: Índice CDR global.
- `mmse_total`: Puntaje total del **Mini-Mental State Examination**.

#### Lenguaje
- `cog_mint_total`: Prueba Multilingüe de Denominación.
- `nat_total_score`: Northwestern Anagram Test.
- `ppvt_total_score`: Peabody Picture Vocabulary Test.
- `exa_rapidnamig_totalcorrect`: Correctas en rapid naming (incluye initial y self-corrected).
- `exa_rapidnamig_totalincorrect`: Incorrectas en rapid naming.
- `exa_rapidnaming_avgreactiontime`: Tiempo de reacción promedio.

#### Atención
- `cog_tmt_a`: Tiempo en completar la parte A del Trail-Making Test (150 = fallo).

#### Short-term memory
- `cog_digits_forward_span`: Span de dígitos directo.

#### Working memory
- `cog_digits_backward_span`: Span de dígitos inverso.

#### Set-shifting
- `cog_tmt_b`: Tiempo en completar la parte B del Trail-Making Test (300 = fallo).

---

## 🔸 Relevantes para ciertos proyectos

### Diagnóstico
- `mri_X`, `mri_questionnaire_X`: 26 variables sobre tipo de imágenes, equipos utilizados y experiencia del participante.

### Demográficas
- `demo_place`: País de nacimiento.
- `demo_resid`: País de residencia.

### Clínicas
- `clinical_substance`, `clinical_substance_spec`, `clinical_substance_years`: Información sobre consumo de drogas.
- `npi_total`: Puntaje total del **Neuropsychiatric Inventory (NPI-Q)**.

### Funcionales
- `udsfaq_total`: Puntaje total del **Pfeffer Functional Activities Questionnaire**.
- `t_adlq_bas_score5`: Actividades básicas de la vida diaria.
- `t_adlq_ins_score5`: Actividades instrumentales.
- `t_adlq_adv_score5`: Actividades avanzadas.

### Estado emocional
- `gad_total`: **Generalized Anxiety Disorder** (cuestionario de ansiedad).
- `gds_total`: **Geriatric Depression Scale** (cuestionario de depresión).
- `uls_total`: **UCLA Loneliness Scale** (escala de soledad).

### Cognitivas

#### Memoria episódica

**Verbal**
- `cog_craft_verb`: Craft inmediato (verbatim).
- `cog_craft_para`: Craft inmediato (parafraseadas).
- `cog_craft_verb_delayed`: Craft diferido (verbatim).
- `cog_craft_para_delayed`: Craft diferido (parafraseadas).

**Visual**
- `cog_benson`: Copia inmediata de la figura compleja de Benson.
- `cog_benson_delayed`: Recuerdo diferido de Benson.
- `cog_benson_recog`: Reconocimiento de la figura original.
- `bha_favrec_totaltruepositive`: True positives en reconocimiento de "Favoritos".
- `bha_favrec_totaltruenegative`: True negatives en reconocimiento de "Favoritos".
- `bha_favrec_totalfalsepositive`: False positives en reconocimiento de "Favoritos".
- `bha_favrec_totalfalsenegative`: False negatives en reconocimiento de "Favoritos".

#### Fluencia verbal
- `cog_category_animals`: Animales en 60 segundos.
- `cog_category_vegetables`: Vegetales en 60 segundos.
- `cog_verbal1_corr`: Palabras con P correctas.
- `cog_verbal2_corr`: Palabras con M correctas.
- `cog_verbal1_reps`, `cog_verbal1_rv`, `cog_verbal2_reps`, `cog_verbal2_rv`: Repeticiones y errores por letra.
- `cog_verbal_corr_total`, `cog_verbal_reps_total`, `cog_verbal_rv_total`: Totales combinados de fluencia fonológica (P + M).

#### Atención
- `cog_tmt_a_err`: Errores en TMT-A.

#### Set-shifting
- `exa_setshifting_totalscore`: Puntaje total en Set Shifting.
- `cog_tmt_b_err`: Errores en TMT-B.

#### Inhibición
- `exa_flanker_totalscore`: Puntaje total en **Flanker** (accuracy + tiempos de reacción).

#### Cognición social
- `minisea_fp_total`: Faux Pas del **Mini-SEA**.
- `minisea_em_total`: Reconocimiento de emociones del **Mini-SEA**.

### Determinantes sociales de la salud
- `Msoc_X`: Cuestionario detallado sobre determinantes sociales, con reportes del participante e informante.


