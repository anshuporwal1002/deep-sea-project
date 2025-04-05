Why Are Deep-Sea Creatures Coming to the Surface?
Causes:

Climate Change & Rising Ocean Temperatures
Warmer waters disrupt natural habitats, forcing species to move to the surface.

Ocean Acidification
CO₂ absorption lowers pH, affecting deep-sea organisms' shells, metabolism, and behavior.

Underwater Earthquakes or Volcanic Activity
Seismic disturbances drive deep-sea species away from their habitats.

Pollution and Oxygen Depletion
Hypoxic zones and toxic environments push marine life toward oxygen-rich layers.

Deep-Sea Mining and Trawling
Human activity disturbs ecosystems, causing displacement.

✅ Solutions:
Early Detection & Monitoring
Use AI, sensors, and real-time data to detect and visualize sightings.

Combat Climate Change
Reduce emissions and promote renewable energy sources.

Ocean Cleanup Initiatives
Reduce plastic waste and participate in conservation efforts.

Protect Marine Ecosystems
Establish marine protected areas and enforce environmental laws.

Public Awareness & Education
Educate communities using digital platforms, visuals, and alerts.
import React from 'react';
import { Waves, Fish, AlertTriangle, Thermometer, Database, Microscope } from 'lucide-react';

function App() {
  return (
    <div className="min-h-screen bg-gradient-to-b from-blue-900 via-blue-800 to-blue-950">
      {/* Hero Section */}
      <header className="relative h-screen flex items-center justify-center text-white px-4">
        <div className="absolute inset-0 bg-black/30 z-10"></div>
        <img 
          src="https://images.unsplash.com/photo-1682687220742-aba13b6e50ba"
          alt="Deep sea background"
          className="absolute inset-0 w-full h-full object-cover"
        />
        <div className="relative z-20 text-center max-w-4xl mx-auto">
          <h1 className="text-6xl font-bold mb-6">Deep Sea Migration</h1>
          <p className="text-xl mb-8">Addressing the unprecedented migration of deep-sea creatures to shallow waters due to climate change</p>
          <Waves className="w-16 h-16 mx-auto animate-bounce" />
        </div>
      </header>

      {/* Problem Statement */}
      <section className="py-20 px-4 bg-blue-900/50 backdrop-blur-sm">
        <div className="max-w-6xl mx-auto">
          <h2 className="text-4xl font-bold text-white mb-12 text-center">The Crisis</h2>
          <div className="grid md:grid-cols-3 gap-8">
            <div className="bg-white/10 backdrop-blur-md p-6 rounded-lg">
              <Thermometer className="w-12 h-12 text-red-400 mb-4" />
              <h3 className="text-xl font-semibold text-white mb-3">Rising Temperatures</h3>
              <p className="text-blue-100">Deep ocean warming is forcing marine life to seek cooler waters closer to the surface</p>
            </div>
            <div className="bg-white/10 backdrop-blur-md p-6 rounded-lg">
              <AlertTriangle className="w-12 h-12 text-yellow-400 mb-4" />
              <h3 className="text-xl font-semibold text-white mb-3">Ecosystem Disruption</h3>
              <p className="text-blue-100">Mass migration is causing unprecedented changes in marine ecosystems</p>
            </div>
            <div className="bg-white/10 backdrop-blur-md p-6 rounded-lg">
              <Fish className="w-12 h-12 text-blue-400 mb-4" />
              <h3 className="text-xl font-semibold text-white mb-3">Species Adaptation</h3>
              <p className="text-blue-100">Deep-sea creatures must adapt to new pressures and light conditions</p>
            </div>
          </div>
        </div>
      </section>

      {/* Solution */}
      <section className="py-20 px-4">
        <div className="max-w-6xl mx-auto">
          <h2 className="text-4xl font-bold text-white mb-12 text-center">Our Solution</h2>
          <div className="grid md:grid-cols-2 gap-12">
            <div className="bg-white/5 backdrop-blur-md p-8 rounded-lg">
              <Database className="w-12 h-12 text-cyan-400 mb-4" />
              <h3 className="text-2xl font-semibold text-white mb-4">Data Collection</h3>
              <p className="text-blue-100">
                Our AI-powered monitoring system tracks deep-sea creature migration patterns and environmental changes in real-time
              </p>
            </div>
            <div className="bg-white/5 backdrop-blur-md p-8 rounded-lg">
              <Microscope className="w-12 h-12 text-purple-400 mb-4" />
              <h3 className="text-2xl font-semibold text-white mb-4">Research & Analysis</h3>
              <p className="text-blue-100">
                Advanced analytics help predict migration trends and develop strategies to protect vulnerable species
              </p>
            </div>
          </div>
        </div>
      </section>

      {/* Call to Action */}
      <section className="py-20 px-4 bg-blue-950/80">
        <div className="max-w-4xl mx-auto text-center">
          <h2 className="text-4xl font-bold text-white mb-6">Join Our Mission</h2>
          <p className="text-xl text-blue-100 mb-8">
            Help us protect our ocean's ecosystems and the creatures that call them home
          </p>
          <button className="bg-blue-500 hover:bg-blue-600 text-white font-semibold py-3 px-8 rounded-lg transition-colors">
            Get Involved
          </button>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-blue-950 text-blue-200 py-8 px-4">
        <div className="max-w-6xl mx-auto text-center">
          <p>© 2024 Deep Sea Migration Project • Google Solution Challenge</p>
        </div>
      </footer>
    </div>
  );
}

export default App;









