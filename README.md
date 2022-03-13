- 👋 Hi, I’m @jorgelima96
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
jorgelima96/jorgelima96 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
	function registrar_evento_selec_urgencia(){
			let select = document.getElementById('f_prioridad')
			select.addEventListener('change', (event) => {
			    console.log(event)
			    alert('f_atencion_A');
			});
		}
