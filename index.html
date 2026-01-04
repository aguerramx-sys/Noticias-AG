import React, { useState, useEffect } from 'react';
import { 
  Globe, 
  MapPin, 
  Building2, 
  TrendingUp, 
  DollarSign, 
  ChevronDown, 
  ChevronUp, 
  Settings2, 
  RefreshCcw, 
  Newspaper, 
  Info, 
  Calendar 
} from 'lucide-react';

const App = () => {
  // Estado para los temas seleccionados
  const [selectedTopics, setSelectedTopics] = useState(['Mundo', 'México', 'Monterrey', 'Finanzas', 'Tipo de Cambio']);
  // Estado para las notas expandidas
  const [expandedNotes, setExpandedNotes] = useState({});
  // Fecha actual
  const [currentDate, setCurrentDate] = useState("");

  useEffect(() => {
    const options = { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' };
    setCurrentDate(new Date().toLocaleDateString('es-MX', options));
  }, []);

  // Datos de noticias (Simulados basados en la fecha actual 2026)
  const newsData = {
    "Mundo": [
      {
        id: "w1",
        title: "EE.UU. establece administración de transición en Venezuela",
        summary: "Tras la captura de Nicolás Maduro, Washington anuncia una fase de transición para estabilizar el país.",
        content: "El gobierno estadounidense ha confirmado que dirigirá temporalmente los esfuerzos de transición en Venezuela tras el operativo militar que resultó en la captura del ex-mandatario. Se busca coordinar con líderes locales una ruta hacia elecciones democráticas mientras se asegura el suministro de ayuda humanitaria y la estabilidad de la industria petrolera."
      },
      {
        id: "w2",
        title: "Tensiones en Irán: Protestas escalan por crisis económica",
        summary: "Manifestaciones masivas en Teherán exigen reformas urgentes ante la caída del poder adquisitivo.",
        content: "Las protestas en Irán han tomado un tono político más severo este fin de semana. Reportes indican enfrentamientos en varias ciudades principales. La comunidad internacional observa de cerca mientras Estados Unidos advierte sobre posibles intervenciones si la violencia contra civiles continúa escalando."
      }
    ],
    "México": [
      {
        id: "mx1",
        title: "Sheinbaum proyecta presupuesto 2026 enfocado en infraestructura ferroviaria",
        summary: "El Gobierno Federal priorizará la expansión de trenes de pasajeros y carga en el presupuesto anual.",
        content: "La presidenta Claudia Sheinbaum anunció que los proyectos ferroviarios serán el eje central del gasto público este año. Se busca consolidar la conectividad del Tren Maya y el Interoceánico, además de iniciar nuevas rutas hacia el norte del país para fortalecer el comercio derivado del nearshoring."
      },
      {
        id: "mx2",
        title: "Sismo de magnitud 5.4 sacude el centro de México",
        summary: "Se reportan daños menores en edificios antiguos y cortes preventivos de energía en la CDMX.",
        content: "El sismo con epicentro en Guerrero activó la alerta sísmica en la capital. Protección Civil reporta saldo blanco en pérdidas humanas, aunque se realizan revisiones estructurales en inmuebles de la zona centro. Los servicios de transporte público operan con normalidad tras protocolos de seguridad."
      }
    ],
    "Monterrey": [
      {
        id: "mty1",
        title: "Nuevo León acelera obras de movilidad rumbo al Mundial 2026",
        summary: "El gobierno estatal intensifica trabajos en las líneas del Metro para cumplir con los plazos de la FIFA.",
        content: "Con el Mundial a la vuelta de la esquina, el estado ha duplicado los turnos de trabajo en las obras viales y de transporte. El gobernador aseguró que Monterrey estará lista para recibir a miles de turistas, destacando la modernización del sistema de autobuses y la conectividad con el Estadio Monterrey."
      },
      {
        id: "mty2",
        title: "Monterrey amanece con mala calidad del aire tras festejos",
        summary: "La zona metropolitana registra altos niveles de partículas tras el uso de pirotecnia y condiciones climáticas.",
        content: "Las estaciones de monitoreo ambiental reportan condiciones de 'muy mala' calidad del aire en Santa Catarina, San Pedro y el Centro de Monterrey. Se recomienda evitar actividades al aire libre mientras las autoridades evalúan declarar una fase de alerta ambiental."
      }
    ],
    "Finanzas": [
      {
        id: "f1",
        title: "Analistas prevén crecimiento del 0.9% para México en 2026",
        summary: "Instituciones financieras ajustan sus proyecciones ante la incertidumbre arancelaria global.",
        content: "A pesar de un inicio de año estable, los analistas del sector privado mantienen cautela sobre el crecimiento del PIB. La principal preocupación radica en las posibles revisiones del T-MEC y la desaceleración de la inversión fija bruta, aunque las remesas siguen siendo un motor importante para el consumo."
      },
      {
        id: "f2",
        title: "Bolsa Mexicana de Valores inicia el año con ligero retroceso",
        summary: "El IPC cae 0.15% en la primera jornada del año arrastrado por el sector minero.",
        content: "La BMV registró una sesión de volatilidad moderada. Empresas del ramo minero y construcción lideraron los descensos, mientras que el sector bancario mostró resiliencia gracias a la expectativa de que el Banco de México mantenga las tasas de interés estables durante el primer trimestre."
      }
    ]
  };

  // Datos del Tipo de Cambio FIX (Oficial)
  const exchangeRate = {
    value: 17.96,
    variation: "-0.08%",
    buy: 17.55,
    sell: 18.37,
    source: "Banxico (FIX)"
  };

  const toggleTopic = (topic) => {
    setSelectedTopics(prev => 
      prev.includes(topic) ? prev.filter(t => t !== topic) : [...prev, topic]
    );
  };

  const toggleExpand = (id) => {
    setExpandedNotes(prev => ({
      ...prev,
      [id]: !prev[id]
    }));
  };

  const getIcon = (topic) => {
    switch(topic) {
      case 'Mundo': return <Globe size={18} className="text-blue-500" />;
      case 'México': return <MapPin size={18} className="text-green-600" />;
      case 'Monterrey': return <Building2 size={18} className="text-orange-500" />;
      case 'Finanzas': return <TrendingUp size={18} className="text-purple-500" />;
      case 'Tipo de Cambio': return <DollarSign size={18} className="text-emerald-500" />;
      default: return <Newspaper size={18} />;
    }
  };

  return (
    <div className="min-h-screen bg-slate-50 font-sans text-slate-900">
      {/* Header */}
      <header className="bg-white border-b border-slate-200 sticky top-0 z-50 shadow-sm">
        <div className="max-w-4xl mx-auto px-4 py-4 flex flex-col md:flex-row md:items-center justify-between gap-4">
          <div>
            <h1 className="text-2xl font-bold bg-gradient-to-r from-slate-900 to-slate-700 bg-clip-text text-transparent">
              NotiResumen MX
            </h1>
            <div className="flex items-center gap-2 mt-1">
              <Calendar size={12} className="text-slate-400" />
              <p className="text-[10px] text-slate-500 uppercase tracking-widest font-bold">
                {currentDate}
              </p>
            </div>
          </div>
          
          <div className="flex items-center gap-2">
            <button 
              onClick={() => window.location.reload()}
              className="p-2 hover:bg-slate-100 rounded-full transition-colors text-slate-600 border border-transparent hover:border-slate-200"
              title="Actualizar noticias"
            >
              <RefreshCcw size={18} />
            </button>
          </div>
        </div>
      </header>

      <main className="max-w-4xl mx-auto px-4 py-6">
        {/* Filtros de Temas */}
        <section className="mb-8 overflow-x-auto pb-2 scrollbar-hide">
          <div className="flex items-center gap-2 mb-3">
            <Settings2 size={14} className="text-slate-400" />
            <span className="text-xs font-bold text-slate-400 uppercase tracking-wider">Filtros</span>
          </div>
          <div className="flex gap-2 min-w-max">
            {['Mundo', 'México', 'Monterrey', 'Finanzas', 'Tipo de Cambio'].map(topic => (
              <button
                key={topic}
                onClick={() => toggleTopic(topic)}
                className={`px-4 py-2 rounded-xl text-xs font-bold transition-all flex items-center gap-2 border ${
                  selectedTopics.includes(topic) 
                  ? 'bg-slate-900 text-white border-slate-900 shadow-md' 
                  : 'bg-white text-slate-600 border-slate-200 hover:border-slate-300'
                }`}
              >
                {getIcon(topic)}
                {topic}
              </button>
            ))}
          </div>
        </section>

        <div className="grid grid-cols-1 md:grid-cols-3 gap-8">
          {/* Columna Principal - Noticias */}
          <div className="md:col-span-2 space-y-12">
            {Object.keys(newsData).map(topic => (
              selectedTopics.includes(topic) && (
                <section key={topic} className="animate-in fade-in slide-in-from-bottom-2 duration-500">
                  <div className="flex items-center gap-3 mb-6">
                    <div className="h-6 w-1.5 bg-indigo-600 rounded-full"></div>
                    <h2 className="text-xl font-black text-slate-800 tracking-tight">{topic}</h2>
                  </div>
                  <div className="space-y-4">
                    {newsData[topic].map(note => (
                      <div 
                        key={note.id} 
                        className="bg-white rounded-xl border border-slate-200 overflow-hidden transition-all group"
                      >
                        <div className="p-6">
                          <h3 className="font-bold text-slate-900 leading-tight mb-3 text-lg group-hover:text-indigo-600 transition-colors">
                            {note.title}
                          </h3>
                          <p className="text-sm text-slate-600 leading-relaxed">
                            {note.summary}
                          </p>
                          
                          <button 
                            onClick={() => toggleExpand(note.id)}
                            className="mt-4 flex items-center gap-1 text-[10px] font-black text-indigo-600 hover:text-indigo-800 transition-colors uppercase tracking-widest"
                          >
                            {expandedNotes[note.id] ? (
                              <>Ver menos <ChevronUp size={14} /></>
                            ) : (
                              <>Expandir nota <ChevronDown size={14} /></>
                            )}
                          </button>

                          {expandedNotes[note.id] && (
                            <div className="mt-5 pt-5 border-t border-slate-100 animate-in slide-in-from-top-2 duration-300">
                              <p className="text-sm text-slate-700 leading-relaxed italic border-l-4 border-slate-100 pl-4">
                                {note.content}
                              </p>
                            </div>
                          )}
                        </div>
                      </div>
                    ))}
                  </div>
                </section>
              )
            ))}
            
            {selectedTopics.length === 0 && (
              <div className="text-center py-24 bg-white rounded-2xl border-2 border-dashed border-slate-200">
                <Newspaper className="mx-auto text-slate-300 mb-4" size={40} />
                <p className="text-slate-500 font-bold">Bandeja vacía</p>
                <p className="text-xs text-slate-400 mt-1">Selecciona temas en la parte superior para ver noticias.</p>
              </div>
            )}
          </div>

          {/* Sidebar - Tipo de Cambio */}
          <div className="space-y-6">
            {selectedTopics.includes('Tipo de Cambio') && (
              <section className="sticky top-24">
                <div className="bg-blue-600 rounded-2xl p-6 text-white border border-blue-500 shadow-lg">
                  <div className="flex justify-between items-start mb-6">
                    <div className="bg-white/20 p-2.5 rounded-xl border border-white/10">
                      <DollarSign size={20} className="text-white" />
                    </div>
                    <span className="text-[10px] font-black bg-blue-500 text-white px-2.5 py-1 rounded-full uppercase tracking-widest border border-blue-400">
                      USD / MXN
                    </span>
                  </div>
                  
                  <p className="text-[10px] font-black text-blue-100 uppercase tracking-widest mb-1">Dólar FIX (Oficial)</p>
                  <div className="flex items-baseline gap-2 mb-8">
                    <span className="text-4xl font-black text-white">${exchangeRate.value.toFixed(2)}</span>
                    <span className="text-xs font-bold text-white bg-blue-500 px-2 py-0.5 rounded-md">
                      {exchangeRate.variation}
                    </span>
                  </div>

                  <div className="grid grid-cols-2 gap-4 border-t border-white/10 pt-6">
                    <div>
                      <p className="text-[10px] uppercase text-blue-100 font-bold mb-1">Compra</p>
                      <p className="text-lg font-bold text-white">${exchangeRate.buy.toFixed(2)}</p>
                    </div>
                    <div>
                      <p className="text-[10px] uppercase text-blue-100 font-bold mb-1">Venta</p>
                      <p className="text-lg font-bold text-white">${exchangeRate.sell.toFixed(2)}</p>
                    </div>
                  </div>

                  <div className="mt-8 p-3 bg-white/10 rounded-xl flex items-center gap-3 border border-white/5">
                    <Info size={14} className="text-blue-100" />
                    <div>
                      <p className="text-[10px] font-bold text-blue-50 font-bold uppercase tracking-tighter">Fuente: Banxico</p>
                    </div>
                  </div>
                </div>

                <div className="mt-6 p-5 bg-blue-50 border border-blue-100 rounded-2xl">
                  <div className="flex items-center gap-2 mb-2">
                    <TrendingUp size={14} className="text-blue-600" />
                    <h4 className="text-[11px] font-black text-blue-900 uppercase tracking-widest">Breves Financieras</h4>
                  </div>
                  <p className="text-xs text-blue-800/80 leading-relaxed">
                    El peso mantiene estabilidad al inicio de 2026. Analistas sugieren monitorear reportes de inflación de la quincena.
                  </p>
                </div>
              </section>
            )}
          </div>
        </div>
      </main>

      <footer className="mt-24 border-t border-slate-200 py-12 bg-white">
        <div className="max-w-4xl mx-auto px-4 text-center">
          <p className="text-[10px] font-black text-slate-400 uppercase tracking-[0.2em] mb-2">
            NOTI-MX DIGITAL
          </p>
          <p className="text-xs text-slate-400">
            Resumen informativo • Monterrey, N.L. • 2026
          </p>
        </div>
      </footer>

      {/* Estilos adicionales para scrollbars */}
      <style>{`
        .scrollbar-hide::-webkit-scrollbar {
          display: none;
        }
        .scrollbar-hide {
          -ms-overflow-style: none;
          scrollbar-width: none;
        }
      `}</style>
    </div>
  );
};

export default App;
