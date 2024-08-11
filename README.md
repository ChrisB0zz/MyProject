# MyProject
from docx import Document
from docx.shared import Inches

# crar un nuevo documento
doc = Document()

# Título del documento
doc.add_heading('Presentación de Solución de IA para Venta de Productos de Salud y Bienestar', level=1)

# Introducción a tu empresa
doc.add_heading('Sobre Nuestra Empresa', level=2)
doc.add_paragraph(
    "Nuestra empresa, SoftDev Solutions, es líder en el desarrollo de software innovador "
    "con enfoque en Inteligencia Artificial y aprendizaje automático. Nuestra misión es "
    "transformar industrias a través de tecnología avanzada y soluciones personalizadas." 
)

    # Misión
doc.add_heading('Misión', level=2)
doc.add_paragraph(
    "Nuestra misión es proporcionar soluciones de software que no solo resuelvan problemas "
    "complejos, sino que también potencien el crecimiento y la eficiencia de nuestros clientes. "
    "Nos esforzamos por ser el socio tecnológico preferido, ofreciendo herramientas que "
    "mejoren la toma de decisiones y optimicen los procesos de negocio."
)

    # Visión
doc.add_heading('Visión', level=2)
doc.add_paragraph(
    "Nuestra visión es liderar la industria del software con innovaciones que marquen una "
    "diferencia significativa en la manera en que las empresas operan y crecen. Buscamos "
    "ser reconocidos por nuestra capacidad para anticipar y adaptarnos a las necesidades del "
    "mercado, ofreciendo soluciones que impulsen el éxito de nuestros clientes."
)

    # Descripción del producto
doc.add_heading('Descripción del Producto', level=2)
doc.add_paragraph(
    "Nuestra solución de IA para la recomendación de productos utiliza algoritmos avanzados "
    "de aprendizaje automático para analizar el historial de compras de los clientes y "
    "sugerir artículos adicionales que se adapten a sus necesidades y preferencias. "
    "Esto no solo mejora la experiencia del cliente, sino que también aumenta las ventas y "
    "la lealtad del cliente."
)

    # Beneficios
doc.add_heading('Beneficios', level=2)
doc.add_paragraph(
    "- Aumento en las ventas a través de recomendaciones personalizadas.\n"
    "- Mejora en la experiencia del cliente con sugerencias relevantes.\n"
    "- Optimización del inventario al identificar patrones de compra.\n"
    "- Análisis detallado del comportamiento del cliente."
)

    # Precios
doc.add_heading('Planes y Precios', level=2)
doc.add_paragraph(
    "Ofrecemos diferentes planes de precios adaptados a las necesidades de tu negocio. "
    "A continuación, se detallan los planes disponibles:\n"
    "1. Plan Básico: $500 al mes - Incluye recomendaciones básicas y soporte técnico.\n"
    "2. Plan Profesional: $1,000 al mes - Incluye recomendaciones avanzadas, análisis de datos, "
    "y soporte prioritario.\n"
    "3. Plan Premium: $2,000 al mes - Incluye todas las características del Plan Profesional, "
    "personalización completa, y soporte dedicado."
)
 
 # Retorno de inversión
doc.add_heading('Retorno de Inversión', level=2)
doc.add_paragraph(
    "Con nuestra solución de IA, puedes esperar un retorno de inversión en menos de 6 meses. "
    "Las recomendaciones personalizadas y la optimización de ventas se traducen en un aumento "
    "directo de los ingresos y una mejora en la satisfacción del cliente, lo que resulta en una "
    "recuperación rápida de la inversión inicial."
)

# Ventajas competitivas
doc.add_heading('Ventajas Competitivas', level=2)
doc.add_paragraph(
    "Elegir nuestra solución significa optar por:\n"
    "- Tecnología de vanguardia y algoritmos avanzados.\n"
    "- Soluciones personalizadas adaptadas a tu negocio.\n"
    "- Soporte técnico excepcional y dedicado.\n"
    "- Flexibilidad y escalabilidad para adaptarse al crecimiento de tu empresa."
)

# Guardar el documento
doc.save('Presentacion_Solucion_IA.docx')
