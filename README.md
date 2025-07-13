# Pensum-Medicina-
// 👶 Semestre 13
{ nombre: "Electiva Profesional 2", id: "electivaprof2", requiere: [], semestre: 13 },
{ nombre: "Ginecología y Obstetricia", id: "gineco", requiere: ["quirurgico"], semestre: 13 },
{ nombre: "Pediatría y Neonatología", id: "pediatria", requiere: ["emergencias"], semestre: 13 },
{ nombre: "Medicina Física y Rehabilitación", id: "rehab", requiere: ["fam"], semestre: 13 },

// 🏥 Semestre 14
{ nombre: "Internado de Cirugía y Traumatología", id: "intcirugia", requiere: ["gineco"], semestre: 14 },
{ nombre: "Internado de Psiquiatría", id: "intpsiquiatria", requiere: ["psiquiatria"], semestre: 14 },
{ nombre: "Trabajo Profesional II", id: "trab2", requiere: ["trab1"], semestre: 14 },
{ nombre: "Internado de Gineco-Obstetricia", id: "intgineco", requiere: ["intcirugia"], semestre: 14 },

// 👶 Semestre 15
{ nombre: "Internado de Pediatría", id: "intpediatria", requiere: ["pediatria"], semestre: 15 },
{ nombre: "Internado de Medicina Interna", id: "intmed", requiere: ["intpediatria"], semestre: 15 },

// 🧑‍⚕️ Semestre 16
{ nombre: "Internado en Atención Primaria y Salud Familiar", id: "intfam", requiere: ["rehab"], semestre: 16 },
{ nombre: "Internado de Medicina Interna Final", id: "intmedfinal", requiere: ["intmed"], semestre: 16 },
{ nombre: "Trabajo Profesional Final", id: "trabfinal", requiere: ["trab2"], semestre: 16 }
