import React, { useState, useEffect } from 'react';

const PraesidiumWebsite = () => {
  const [mobileMenuOpen, setMobileMenuOpen] = useState(false);
  const [popupOpen, setPopupOpen] = useState(false);
  
  // Function to toggle mobile menu
  const toggleMobileMenu = (isOpen) => {
    setMobileMenuOpen(isOpen);
  };
  
  // Function to toggle contact popup
  const toggleContactPopup = () => {
    setPopupOpen(!popupOpen);
  };
  
  // Function to scroll to section
  const scrollToSection = (id) => {
    const element = document.getElementById(id);
    if (element) {
      window.scrollTo({
        top: element.offsetTop - 80,
        behavior: 'smooth'
      });
      toggleMobileMenu(false);
    }
  };
  
  // Add animation for sections
  useEffect(() => {
    const observerOptions = {
      root: null,
      rootMargin: '0px',
      threshold: 0.1
    };
    
    const handleIntersect = (entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('opacity-100');
          entry.target.classList.remove('opacity-0');
        }
      });
    };
    
    const observer = new IntersectionObserver(handleIntersect, observerOptions);
    
    const sections = document.querySelectorAll('section');
    sections.forEach(section => {
      if (section.id) {
        observer.observe(section);
      }
    });
    
    // Cleanup
    return () => {
      sections.forEach(section => {
        if (section.id) {
          observer.unobserve(section);
        }
      });
    };
  }, []);
  
  // Cofounder data
  const cofounders = [
    {
      name: "Sarah Johnson",
      designation: "CEO & Co-Founder",
      email: "sarah@praesidiumsystems.com",
      photo: "/api/placeholder/150/150" // Placeholder for cofounder 1 photo
    },
    {
      name: "Michael Chen",
      designation: "CTO & Co-Founder",
      email: "michael@praesidiumsystems.com",
      photo: "/api/placeholder/150/150" // Placeholder for cofounder 2 photo
    }
  ];
  
  return (
    <div className="min-h-screen bg-gray-50 font-sans">
      {/* Header */}
      <header className="fixed w-full bg-white shadow-md z-50">
        <div className="container mx-auto px-4 py-4 flex justify-between items-center">
          <div className="flex items-center gap-2">
            {/* Using your actual logo */}
            <img src="/images/logo.png" alt="Praesidium Logo" className="h-10" />
            <span className="text-xl font-bold text-gray-900">Praesidium Systems</span>
          </div>
          
          {/* Desktop Navigation */}
          <nav className="hidden md:flex items-center gap-6">
            <button onClick={() => scrollToSection('features')} className="text-gray-700 hover:text-blue-600 transition-colors">Features</button>
            <button onClick={() => scrollToSection('how-it-works')} className="text-gray-700 hover:text-blue-600 transition-colors">How It Works</button>
            <button onClick={() => scrollToSection('deployment')} className="text-gray-700 hover:text-blue-600 transition-colors">Deployment</button>
            <button onClick={() => scrollToSection('contact')} className="px-5 py-2 bg-blue-600 text-white rounded-full hover:bg-blue-700 transition-colors">Contact Us</button>
          </nav>
          
          {/* Mobile Menu Button */}
          <button 
            onClick={() => toggleMobileMenu(true)} 
            className="md:hidden text-gray-700"
          >
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="h-6 w-6">
              <line x1="3" y1="12" x2="21" y2="12"></line>
              <line x1="3" y1="6" x2="21" y2="6"></line>
              <line x1="3" y1="18" x2="21" y2="18"></line>
            </svg>
          </button>
        </div>
      </header>

      {/* Mobile Menu */}
      <div className={`fixed inset-0 bg-gray-900 bg-opacity-50 z-50 md:hidden ${mobileMenuOpen ? '' : 'hidden'}`}>
        <div className="h-full w-64 bg-white p-6 flex flex-col shadow-lg">
          <div className="flex justify-between items-center mb-6">
            <div className="flex items-center gap-2">
              <img src="/api/placeholder/28/28" alt="Praesidium Logo" className="h-7" />
              <span className="text-lg font-bold text-gray-900">Praesidium</span>
            </div>
            <button onClick={() => toggleMobileMenu(false)}>
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="h-6 w-6 text-gray-700">
                <line x1="18" y1="6" x2="6" y2="18"></line>
                <line x1="6" y1="6" x2="18" y2="18"></line>
              </svg>
            </button>
          </div>
          <nav className="flex flex-col gap-4">
            <button 
              onClick={() => scrollToSection('features')} 
              className="text-gray-700 hover:text-blue-600 transition-colors text-left py-2 border-b border-gray-100"
            >
              Features
            </button>
            <button 
              onClick={() => scrollToSection('how-it-works')} 
              className="text-gray-700 hover:text-blue-600 transition-colors text-left py-2 border-b border-gray-100"
            >
              How It Works
            </button>
            <button 
              onClick={() => scrollToSection('deployment')} 
              className="text-gray-700 hover:text-blue-600 transition-colors text-left py-2 border-b border-gray-100"
            >
              Deployment
            </button>
            <button 
              onClick={() => scrollToSection('contact')} 
              className="mt-4 px-5 py-2 bg-blue-600 text-white rounded-full hover:bg-blue-700 transition-colors"
            >
              Contact Us
            </button>
          </nav>
        </div>
      </div>

      {/* Hero Section */}
      <section className="pt-32 pb-20 bg-gradient-to-br from-blue-50 to-indigo-50">
        <div className="container mx-auto px-4">
          <div className="flex flex-col md:flex-row items-center justify-between gap-12">
            <div className="md:w-1/2 space-y-6">
              <h1 className="text-4xl md:text-5xl font-bold text-gray-900 leading-tight">
                AI Compliance <span className="text-blue-600">Simplified</span>
              </h1>
              <p className="text-xl text-gray-600 max-w-lg">
                Monitor, audit, and ensure regulatory compliance for your AI models with our comprehensive governance platform.
              </p>
              <div className="flex flex-col sm:flex-row gap-4">
                <button 
                  onClick={() => scrollToSection('contact')}
                  className="px-6 py-3 bg-blue-600 text-white rounded-full hover:bg-blue-700 transition-colors flex items-center justify-center gap-2"
                >
                  Request Demo
                  <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="h-5 w-5">
                    <polyline points="9 18 15 12 9 6"></polyline>
                  </svg>
                </button>
                <button 
                  onClick={() => scrollToSection('features')}
                  className="px-6 py-3 border border-blue-600 text-blue-600 rounded-full hover:bg-blue-50 transition-colors flex items-center justify-center"
                >
                  Explore Features
                </button>
              </div>
            </div>
            <div className="md:w-1/2">
              {/* Using your actual dashboard demo image */}
              <img 
                src="/images/dashboard-demo.png" 
                alt="AI Compliance Dashboard" 
                className="rounded-lg shadow-xl"
              />
            </div>
          </div>
        </div>
      </section>

      {/* Features Section */}
      <section 
        id="features" 
        className="py-20 bg-white opacity-0 transition-opacity duration-1000"
      >
        <div className="container mx-auto px-4">
          <div className="text-center mb-16">
            <h2 className="text-3xl font-bold text-gray-900 mb-4">Comprehensive AI Governance Platform</h2>
            <p className="text-xl text-gray-600 max-w-3xl mx-auto">
              From hallucination detection to regulatory compliance, our platform offers end-to-end governance solutions.
            </p>
          </div>
          
          <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            {/* Feature 1 */}
            <div className="bg-white p-6 rounded-lg shadow-lg border border-gray-100 hover:shadow-xl transition-shadow">
              <div className="inline-block p-3 bg-blue-100 rounded-lg text-blue-600 mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="h-6 w-6">
                  <circle cx="11" cy="11" r="8"></circle>
                  <line x1="21" y1="21" x2="16.65" y2="16.65"></line>
                </svg>
              </div>
              <h3 className="text-xl font-bold text-gray-900 mb-3">Hallucination Detection</h3>
              <p className="text-gray-600">
                Automatically identify and flag when your models generate inaccurate or fabricated information through advanced verification techniques.
              </p>
            </div>
            
            {/* Feature 2 */}
            <div className="bg-white p-6 rounded-lg shadow-lg border border-gray-100 hover:shadow-xl transition-shadow">
              <div className="inline-block p-3 bg-blue-100 rounded-lg text-blue-600 mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="h-6 w-6">
                  <path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"></path>
                </svg>
              </div>
              <h3 className="text-xl font-bold text-gray-900 mb-3">Compliance Monitoring</h3>
              <p className="text-gray-600">
                Continuously track model outputs for alignment with industry regulations like GDPR, HIPAA, and your custom policies.
              </p>
            </div>
            
            {/* Feature 3 */}
            <div className="bg-white p-6 rounded-lg shadow-lg border border-gray-100 hover:shadow-xl transition-shadow">
              <div className="inline-block p-3 bg-blue-100 rounded-lg text-blue-600 mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="h-6 w-6">
                  <path d="m21.73 18-8-14a2 2 0 0 0-3.48 0l-8 14A2 2 0 0 0 4 21h16a2 2 0 0 0 1.73-3Z"></path>
                  <line x1="12" y1="9" x2="12" y2="13"></line>
                  <line x1="12" y1="17" x2="12.01" y2="17"></line>
                </svg>
              </div>
              <h3 className="text-xl font-bold text-gray-900 mb-3">Agency Analysis</h3>
              <p className="text-gray-600">
                Detect and prevent situations where AI models overstate their capabilities or make unauthorized commitments.
              </p>
            </div>
            
            {/* Feature 4 */}
            <div className="bg-white p-6 rounded-lg shadow-lg border border-gray-100 hover:shadow-xl transition-shadow">
              <div className="inline-block p-3 bg-blue-100 rounded-lg text-blue-600 mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="h-6 w-6">
                  <line x1="18" y1="20" x2="18" y2="10"></line>
                  <line x1="12" y1="20" x2="12" y2="4"></line>
                  <line x1="6" y1="20" x2="6" y2="14"></line>
                </svg>
              </div>
              <h3 className="text-xl font-bold text-gray-900 mb-3">Performance Tracking</h3>
              <p className="text-gray-600">
                Comprehensive dashboards to track model performance, version history, and dataset lineage over time.
              </p>
            </div>
            
            {/* Feature 5 */}
            <div className="bg-white p-6 rounded-lg shadow-lg border border-gray-100 hover:shadow-xl transition-shadow">
              <div className="inline-block p-3 bg-blue-100 rounded-lg text-blue-600 mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="h-6 w-6">
                  <path d="M12.22 2h-.44a2 2 0 0 0-2 2v.18a2 2 0 0 1-1 1.73l-.43.25a2 2 0 0 1-2 0l-.15-.08a2 2 0 0 0-2.73.73l-.22.38a2 2 0 0 0 .73 2.73l.15.1a2 2 0 0 1 1 1.72v.51a2 2 0 0 1-1 1.74l-.15.09a2 2 0 0 0-.73 2.73l.22.38a2 2 0 0 0 2.73.73l.15-.08a2 2 0 0 1 2 0l.43.25a2 2 0 0 1 1 1.73V20a2 2 0 0 0 2 2h.44a2 2 0 0 0 2-2v-.18a2 2 0 0 1 1-1.73l.43-.25a2 2 0 0 1 2 0l.15.08a2 2 0 0 0 2.73-.73l.22-.39a2 2 0 0 0-.73-2.73l-.15-.08a2 2 0 0 1-1-1.74v-.5a2 2 0 0 1 1-1.74l.15-.09a2 2 0 0 0 .73-2.73l-.22-.38a2 2 0 0 0-2.73-.73l-.15.08a2 2 0 0 1-2 0l-.43-.25a2 2 0 0 1-1-1.73V4a2 2 0 0 0-2-2z"></path>
                  <circle cx="12" cy="12" r="3"></circle>
                </svg>
              </div>
              <h3 className="text-xl font-bold text-gray-900 mb-3">Customizable Frameworks</h3>
              <p className="text-gray-600">
                Define and enforce your own policies, regulatory frameworks, and documentation requirements.
              </p>
            </div>
            
            {/* Feature 6 */}
            <div className="bg-white p-6 rounded-lg shadow-lg border border-gray-100 hover:shadow-xl transition-shadow">
              <div className="inline-block p-3 bg-blue-100 rounded-lg text-blue-600 mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="h-6 w-6">
                  <path d="M16 18 22 12 16 6"></path>
                  <path d="M8 6 2 12 8 18"></path>
                </svg>
              </div>
              <h3 className="text-xl font-bold text-gray-900 mb-3">Seamless Integration</h3>
              <p className="text-gray-600">
                Connects with your existing ML ecosystem and major LLM providers for frictionless adoption.
              </p>
            </div>
          </div>
        </div>
      </section>

      {/* How It Works Section */}
      <section 
        id="how-it-works" 
        className="py-20 bg-blue-50 opacity-0 transition-opacity duration-1000"
      >
        <div className="container mx-auto px-4">
          <div className="text-center mb-16">
            <h2 className="text-3xl font-bold text-gray-900 mb-4">How It Works</h2>
            <p className="text-xl text-gray-600 max-w-3xl mx-auto">
              Our platform integrates seamlessly with your AI workflow in four simple steps
            </p>
          </div>
          
          <div className="max-w-4xl mx-auto space-y-12">
            {/* Step 1 */}
            <div className="flex flex-col md:flex-row gap-6 items-start">
              <div className="flex-shrink-0 w-12 h-12 rounded-full bg-blue-600 text-white flex items-center justify-center font-bold text-xl">
                1
              </div>
              <div>
                <h3 className="text-xl font-bold text-gray-900 mb-2">Connect Your Models</h3>
                <p className="text-gray-600">
                  Integrate with APIs from OpenAI, Claude, Gemini, or use lightweight local LLMs for cost efficiency. Our platform offers flexible connection options for all major providers.
                </p>
              </div>
            </div>
            
            {/* Other steps... */}
            <div className="flex flex-col md:flex-row gap-6 items-start">
              <div className="flex-shrink-0 w-12 h-12 rounded-full bg-blue-600 text-white flex items-center justify-center font-bold text-xl">
                2
              </div>
              <div>
                <h3 className="text-xl font-bold text-gray-900 mb-2">Define Your Governance Framework</h3>
                <p className="text-gray-600">
                  Customize compliance requirements, regulatory frameworks, and policy documentation specific to your organization and industry needs.
                </p>
              </div>
            </div>
            
            <div className="flex flex-col md:flex-row gap-6 items-start">
              <div className="flex-shrink-0 w-12 h-12 rounded-full bg-blue-600 text-white flex items-center justify-center font-bold text-xl">
                3
              </div>
              <div>
                <h3 className="text-xl font-bold text-gray-900 mb-2">Monitor & Evaluate</h3>
                <p className="text-gray-600">
                  Continuously track model performance, detect hallucinations, and identify compliance gaps in real-time through our advanced monitoring dashboard.
                </p>
              </div>
            </div>
            
            <div className="flex flex-col md:flex-row gap-6 items-start">
              <div className="flex-shrink-0 w-12 h-12 rounded-full bg-blue-600 text-white flex items-center justify-center font-bold text-xl">
                4
              </div>
              <div>
                <h3 className="text-xl font-bold text-gray-900 mb-2">Report & Improve</h3>
                <p className="text-gray-600">
                  Generate comprehensive reports for stakeholders and use insights to improve model performance and compliance over time.
                </p>
              </div>
            </div>
          </div>
          
          {/* Integrations */}
          <div className="mt-20">
            <h3 className="text-xl font-bold text-gray-900 text-center mb-8">Works with all major AI providers</h3>
            <div className="flex flex-wrap justify-center items-center gap-8 md:gap-16">
              <div className="text-center opacity-70 hover:opacity-100 transition-opacity">
                <img src="/images/partner-openai.png" alt="OpenAI" className="mx-auto h-10" />
                <span className="text-sm text-gray-600 mt-2 block">OpenAI</span>
              </div>
              <div className="text-center opacity-70 hover:opacity-100 transition-opacity">
                <img src="/images/partner-anthropic.png" alt="Anthropic" className="mx-auto h-10" />
                <span className="text-sm text-gray-600 mt-2 block">Anthropic</span>
              </div>
              <div className="text-center opacity-70 hover:opacity-100 transition-opacity">
                <img src="/images/partner-google.png" alt="Google" className="mx-auto h-10" />
                <span className="text-sm text-gray-600 mt-2 block">Google</span>
              </div>
              <div className="text-center opacity-70 hover:opacity-100 transition-opacity">
                <img src="/images/partner-aws.png" alt="AWS" className="mx-auto h-10" />
                <span className="text-sm text-gray-600 mt-2 block">AWS</span>
              </div>
              <div className="text-center opacity-70 hover:opacity-100 transition-opacity">
                <img src="/images/partner-azure.png" alt="Azure" className="mx-auto h-10" />
                <span className="text-sm text-gray-600 mt-2 block">Azure</span>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* Deployment Section */}
      <section 
        id="deployment" 
        className="py-20 bg-white opacity-0 transition-opacity duration-1000"
      >
        <div className="container mx-auto px-4">
          <div className="text-center mb-16">
            <h2 className="text-3xl font-bold text-gray-900 mb-4">Flexible Deployment Options</h2>
            <p className="text-xl text-gray-600 max-w-3xl mx-auto">
              Deploy our platform wherever it makes the most sense for your organization
            </p>
          </div>
          
          <div className="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-5xl mx-auto">
            {/* Cloud */}
            <div className="bg-white p-6 rounded-lg shadow-lg border border-gray-100 hover:border-blue-200 hover:shadow-xl transition-all">
              <div className="mb-4 text-blue-600">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="h-10 w-10">
                  <rect x="2" y="2" width="20" height="8" rx="2" ry="2"></rect>
                  <rect x="2" y="14" width="20" height="8" rx="2" ry="2"></rect>
                  <line x1="6" y1="6" x2="6.01" y2="6"></line>
                  <line x1="6" y1="18" x2="6.01" y2="18"></line>
                </svg>
              </div>
              <h3 className="text-xl font-bold text-gray-900 mb-3">Cloud Deployment</h3>
              <p className="text-gray-600 mb-4">
                Deploy on AWS, Azure, or Google Cloud with our managed service for maximum convenience and scalability.
              </p>
              <a href="#contact" className="text-blue-600 font-medium flex items-center gap-1 hover:gap-2 transition-all">
                Learn more
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="h-4 w-4">
                  <polyline points="9 18 15 12 9 6"></polyline>
                </svg>
              </a>
            </div>
            
            {/* On-Premises */}
            <div className="bg-white p-6 rounded-lg shadow-lg border border-gray-100 hover:border-blue-200 hover:shadow-xl transition-all">
              <div className="mb-4 text-blue-600">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="h-10 w-10">
                  <ellipse cx="12" cy="5" rx="9" ry="3"></ellipse>
                  <path d="M21 12c0 1.66-4 3-9 3s-9-1.34-9-3"></path>
                  <path d="M3 5v14c0 1.66 4 3 9 3s9-1.34 9-3V5"></path>
                </svg>
              </div>
              <h3 className="text-xl font-bold text-gray-900 mb-3">On-Premises</h3>
              <p className="text-gray-600 mb-4">
                Install on your own hardware for complete control and compliance with data residency requirements.
              </p>
              <a href="#contact" className="text-blue-600 font-medium flex items-center gap-1 hover:gap-2 transition-all">
                Learn more
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="h-4 w-4">
                  <polyline points="9 18 15 12 9 6"></polyline>
                </svg>
              </a>
            </div>
            
            {/* VPC */}
            <div className="bg-white p-6 rounded-lg shadow-lg border border-gray-100 hover:border-blue-200 hover:shadow-xl transition-all">
              <div className="mb-4 text-blue-600">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="h-10 w-10">
                  <rect x="3" y="11" width="18" height="11" rx="2" ry="2"></rect>
                  <path d="M7 11V7a5 5 0 0 1 10 0v4"></path>
                </svg>
              </div>
              <h3 className="text-xl font-bold text-gray-900 mb-3">VPC Deployment</h3>
              <p className="text-gray-600 mb-4">
                Deploy within your Virtual Private Cloud for enhanced security and privacy while maintaining flexibility.
              </p>
              <a href="#contact" className="text-blue-600 font-medium flex items-center gap-1 hover:gap-2 transition-all">
                Learn more
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="h-4 w-4">
                  <polyline points="9 18 15 12 9 6"></polyline>
                </svg>
              </a>
            </div>
          </div>
        </div>
      </section>

      {/* Testimonials Section */}
      <section id="testimonials" className="py-20 bg-gray-50 opacity-0 transition-opacity duration-1000">
        <div className="container mx-auto px-4">
          <div className="text-center mb-16">
            <h2 className="text-3xl font-bold text-gray-900 mb-4">Trusted by Industry Leaders</h2>
            <p className="text-xl text-gray-600 max-w-3xl mx-auto">
              See what our customers say about Praesidium Compliance Systems
            </p>
          </div>
          
          <div className="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-5xl mx-auto">
            {/* Testimonial 1 */}
            <div className="bg-white p-6 rounded-lg shadow-md border border-gray-100">
              <div className="flex items-center mb-4">
                <div className="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center text-blue-600 font-bold">
                  FT
                </div>
                <div className="ml-4">
                  <h4 className="font-bold">Financial Tech Inc.</h4>
                  <p className="text-gray-600 text-sm">Director of AI Governance</p>
                </div>
              </div>
              <p className="text-gray-700">
                "Praesidium has transformed our AI compliance processes. We're now able to identify potential issues before they affect our customers, saving us time and resources."
              </p>
            </div>
            
            {/* Testimonial 2 */}
            <div className="bg-white p-6 rounded-lg shadow-md border border-gray-100">
              <div className="flex items-center mb-4">
                <div className="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center text-blue-600 font-bold">
                  HC
                </div>
                <div className="ml-4">
                  <h4 className="font-bold">HealthCare Solutions</h4>
                  <p className="text-gray-600 text-sm">Chief Compliance Officer</p>
                </div>
              </div>
              <p className="text-gray-700">
                "With stringent HIPAA requirements, we needed a solution that could ensure our AI models maintain compliance. Praesidium delivers this with unprecedented visibility and control."
              </p>
            </div>
          </div>
        </div>
      </section>

      {/* CTA Section with Contact Popup */}
      <section 
        id="contact" 
        className="py-20 bg-gradient-to-r from-blue-600 to-indigo-700 text-white opacity-0 transition-opacity duration-1000"
      >
        <div className="container mx-auto px-4 text-center">
          <h2 className="text-3xl font-bold mb-6">Ready to Ensure AI Compliance?</h2>
          <p className="text-xl max-w-2xl mx-auto mb-8 opacity-90">
            Get in touch with our team for a personalized demo and discover how our platform can help your organization maintain regulatory integrity.
          </p>
          <div className="flex flex-col sm:flex-row gap-4 justify-center">
            <button 
              onClick={toggleContactPopup}
              className="px-8 py-3 bg-white text-blue-600 rounded-full hover:bg-gray-100 transition-colors font-medium"
            >
              Meet Our Team
            </button>
            <button className="px-8 py-3 bg-transparent border border-white text-white rounded-full hover:bg-white/10 transition-colors font-medium">
              Contact Sales
            </button>
          </div>
        </div>
      </section>

      {/* Contact Popup */}
      {popupOpen && (
        <div className="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 p-4">
          <div className="bg-white rounded-xl shadow-2xl p-6 max-w-2xl w-full relative">
            <button 
              onClick={toggleContactPopup}
              className="absolute top-4 right-4 text-gray-500 hover:text-gray-700"
            >
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="h-6 w-6">
                <line x1="18" y1="6" x2="6" y2="18"></line>
                <line x1="6" y1="6" x2="18" y2="18"></line>
              </svg>
            </button>
            
            <h3 className="text-2xl font-bold text-gray-900 mb-6 text-center">Meet Our Co-Founders</h3>
            
            <div className="grid grid-cols-1 md:grid-cols-2 gap-8">
              {cofounders.map((founder, index) => (
                <div key={index} className="flex flex-col items-center">
                  <img 
                    src={index === 0 ? "/images/cofounder1.jpg" : "/images/cofounder2.jpg"} 
                    alt={founder.name} 
                    className="w-32 h-32 rounded-full object-cover mb-4 border-4 border-blue-100"
                  />
                  <h4 className="font-bold text-xl text-gray-900">{founder.name}</h4>
                  <p className="text-blue-600 mb-2">{founder.designation}</p>
                  <a 
                    href={`mailto:${founder.email}`} 
                    className="text-gray-600 hover:text-blue-600 transition-colors flex items-center gap-1"
                  >
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="h-4 w-4">
                      <path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path>
                      <polyline points="22,6 12,13 2,6"></polyline>
                    </svg>
                    {founder.email}
                  </a>
                </div>
              ))}
            </div>
            
            <div className="mt-8 text-center">
              <p className="text-gray-600 mb-4">
                Schedule a demo with our team to see how our platform can help your organization achieve AI compliance.
              </p>
              <button className="px-6 py-2 bg-blue-600 text-white rounded-full hover:bg-blue-700 transition-colors">
                Schedule a Demo
              </button>
            </div>
          </div>
        </div>
      )}

      {/* Footer */}
      <footer className="bg-gray-900 text-white py-12">
        <div className="container mx-auto px-4">
          <div className="grid grid-cols-1 md:grid-cols-4 gap-8 mb-8">
            <div>
              <div className="flex items-center gap-2 mb-4">
                <img src="/api/placeholder/24/24" alt="Praesidium Logo" className="h-6" />
                <span className="text-lg font-bold">Praesidium Systems</span>
              </div>
              <p className="text-gray-400">
                AI Governance, simplified.
              </p>
            </div>
            
            <div>
              <h3 className="font-bold mb-4">Product</h3>
              <ul className="space-y-2">
                <li><a href="#features" className="text-gray-400 hover:text-white transition-colors">Features</a></li>
                <li><a href="#how-it-works" className="text-gray-400 hover:text-white transition-colors">How It Works</a></li>
                <li><a href="#deployment" className="text-gray-400 hover:text-white transition-colors">Deployment</a></li>
                <li><a href="#" className="text-gray-400 hover:text-white transition-colors">Pricing</a></li>
              </ul>
            </div>
            
            <div>
              <h3 className="font-bold mb-4">Resources</h3>
              <ul className="space-y-2">
                <li><a href="#" className="text-gray-400 hover:text-white transition-colors">Documentation</a></li>
                <li><a href="#" className="text-gray-400 hover:text-white transition-colors">API Reference</a></li>
                <li><a href="#" className="text-gray-400 hover:text-white transition-colors">Blog</a></li>
                <li><a href="#" className="text-gray-400 hover:text-white transition-colors">Support</a></li>
              </ul>
            </div>
            
            <div>
              <h3 className="font-bold mb-4">Company</h3>
              <ul className="space-y-2">
                <li><a href="#" className="text-gray-400 hover:text-white transition-colors">About Us</a></li>
                <li><a href="#" className="text-gray-400 hover:text-white transition-colors">Careers</a></li>
                <li><a href="#contact" className="text-gray-400 hover:text-white transition-colors">Contact</a></li>
                <li><a href="#" className="text-gray-400 hover:text-white transition-colors">Privacy Policy</a></li>
              </ul>
            </div>
          </div>
          
          <div className="border-t border-gray-800 pt-8 mt-8 text-center text-gray-500 text-sm">
            &copy; {new Date().getFullYear()} Praesidium Compliance Systems Corporation. All rights reserved.
          </div>
        </div>
      </footer>
    </div>
  );
};

export default PraesidiumWebsite;
