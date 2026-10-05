import React, { useState, useEffect, useRef } from 'react';
import { 
  Building2, Search, MapPin, Sparkles, Shield, HelpCircle, User, 
  LogIn, UserPlus, Globe, Sun, Moon, CheckCircle2, Award, ArrowRight,
  Home, DollarSign, Layers, Phone, Mail, FileText, ChevronRight,
  Filter, Grid, Map, Star, PlusCircle, CreditCard, RefreshCw, AlertCircle,
  Sliders, Eye, Share2, Heart, Send, Check, X, Bookmark, Zap, PhoneCall,
  Video, Compass, Database, Briefcase, Settings, Lock, CheckSquare, MessageSquare
} from 'lucide-react';

const TRANSLATIONS = {
  en: {
    brand: "NINJA ESTATEBOT",
    tagline: "Find Property Smarter with AI",
    subheading: "Search properties, manage leads, communicate safely and grow your real-estate business with AI.",
    navHome: "Home",
    navBuy: "Buy",
    navRent: "Rent",
    navSell: "Sell / List",
    navLand: "Land & Plots",
    navProjects: "Projects",
    navAgents: "Agents",
    navAI: "Ninja AI",
    navPremium: "Premium",
    navCredits: "Credits",
    navSafety: "Safety",
    navHelp: "Help",
    login: "Login",
    createAccount: "Create Account",
    startFreeTrial: "Start Free Trial",
    searchPlaceholder: "Search city, locality, project...",
    searchBtn: "Search Properties",
    askAI: "Ask Ninja AI",
    freeTrialBanner: "15 DAYS FREE TRIAL - Explore All Premium SaaS & AI Tools Instantly",
    startFree: "START FREE",
    exploreProps: "EXPLORE PROPERTIES",
    disclaimer: "Disclaimer: NINJA ESTATEBOT is a technology platform connecting buyers, sellers, agents, and builders. We are not a direct property owner or seller.",
    dashboardTitle: "Seller & Landowner Dashboard",
    addNewProperty: "List New Property / Land",
    myListings: "My Active Listings",
    leads: "Captured Leads",
    wallet: "Credits & Subscription",
    surveyNo: "Survey No.",
    soilType: "Soil Type",
    waterSource: "Water Source",
    legalTitle: "Clear Title",
    priceInINR: "Price (₹)",
    uploadImages: "Upload Photos & Drone Shots",
    submitListing: "Publish Listing Securely",
    buyTab: "Buy",
    rentTab: "Rent",
    landTab: "Land & Agriculture",
    commercialTab: "Commercial",
    projectsTab: "Projects"
  },
  ta: {
    brand: "நிஞ்சா எஸ்டேட் பாட்",
    tagline: "AI மூலம் புத்திசாலித்தனமாக சொத்துக்களைத் தேடுங்கள்",
    subheading: "சொத்துக்களைத் தேடுங்கள், வாடிக்கையாளர்களை நிர்வகிக்கவும் மற்றும் உங்கள் வணிகத்தை வளர்க்கவும்.",
    navHome: "முகப்பு",
    navBuy: "வாங்கு",
    navRent: "வாடகை",
    navSell: "விற்க / பட்டியல்",
    navLand: "நிலம் & பண்ணை",
    navProjects: "திட்டங்கள்",
    navAgents: "முகவர்கள்",
    navAI: "நிஞ்சா AI",
    navPremium: "பிரீமியம்",
    navCredits: "கிரெடிட்ஸ்",
    navSafety: "பாதுகாப்பு",
    navHelp: "உதவி",
    login: "உள்நுழை",
    createAccount: " கணக்கு தொடங்கு",
    startFreeTrial: "15 நாட்கள் இலவச சோதனை",
    searchPlaceholder: "நகரம் அல்லது பகுதியைத் தேடுங்கள்...",
    searchBtn: "சொத்துக்களைத் தேடு",
    askAI: "நிஞ்சா AI இடம் கேள்",
    freeTrialBanner: "15 நாட்கள் இலவச சோதனை - அனைத்து பிரீமியம் மற்றும் AI கருவிகளையும் உடனடியாக முயற்சிக்கவும்",
    startFree: "இலவசமாக தொடங்கு",
    exploreProps: "சொத்துக்களைப் பார்",
    disclaimer: "பொறுப்பு துறப்பு: நிஞ்சா எஸ்டேட் பாட் ஒரு தொழில்நுட்ப தளமாகும். நாங்கள் நேரடி சொத்து உரிமையாளர்கள் அல்ல.",
    dashboardTitle: "விற்பனையாளர் மற்றும் நில உரிமையாளர் டாஷ்போர்டு",
    addNewProperty: "புதிய சொத்து / நிலத்தை பட்டியலிடுங்கள்",
    myListings: "எனது பட்டியல்கள்",
    leads: "லீடுகள்",
    wallet: "கிரெடிட்ஸ் & சந்தா",
    surveyNo: "சர்வே எண்",
    soilType: "மண் வகை",
    waterSource: "நீர் ஆதாரம்",
    legalTitle: "தெளிவான தலைப்பு",
    priceInINR: "விலை (₹)",
    uploadImages: "புகைப்படங்கள் & ட்ரோன் காட்சிகளைப் பதிவேற்றுக",
    submitListing: "பட்டியலை வெளியிடு",
    buyTab: "வாங்கு",
    rentTab: "வாடகை",
    landTab: "நிலம்",
    commercialTab: "வணிகம்",
    projectsTab: "திட்டங்கள்"
  },
  hi: {
    brand: "निंजा एस्टेटबॉट",
    tagline: "AI के साथ स्मार्ट तरीके से संपत्ति खोजें",
    subheading: "संपत्तियां खोजें, लीड प्रबंधित करें, सुरक्षित रूप से संवाद करें और एआई के साथ अपने रियल एस्टेट व्यवसाय को बढ़ाएं।",
    navHome: "होम",
    navBuy: "खरीदें",
    navRent: "किराये पर",
    navSell: "बेचें / सूची",
    navLand: "भूमि और भूखंड",
    navProjects: "प्रोजेक्ट्स",
    navAgents: "एजेंट",
    navAI: "निंजा AI",
    navPremium: "प्रीमियम",
    navCredits: "क्रेडिट",
    navSafety: "सुरक्षा",
    navHelp: "सहायता",
    login: "लॉगिन",
    createAccount: "खाता बनाएं",
    startFreeTrial: "15 दिन का निःशुल्क परीक्षण",
    searchPlaceholder: "शहर, इलाका खोजें...",
    searchBtn: "संपत्तियां खोजें",
    askAI: "निंजा AI से पूछें",
    freeTrialBanner: "15 दिन का निःशुल्क परीक्षण - सभी प्रीमियम SaaS और AI टूल तुरंत आज़माएं",
    startFree: "मुफ्त में शुरू करें",
    exploreProps: "संपत्तियां देखें",
    disclaimer: "अस्वीकरण: निंजा एस्टेटबॉट एक तकनीकी मंच है। हम सीधे संपत्ति के मालिक या विक्रेता नहीं हैं।",
    dashboardTitle: "विक्रेता और भूस्वामी डैशबोर्ड",
    addNewProperty: "नई संपत्ति / भूमि सूचीबद्ध करें",
    myListings: "मेरी सक्रिय सूचियां",
    leads: "कैप्चर किए गए लीड",
    wallet: "क्रेडिट और सदस्यता",
    surveyNo: "सर्वे संख्या",
    soilType: "मिट्टी का प्रकार",
    waterSource: "जल स्रोत",
    legalTitle: "स्पष्ट शीर्षक",
    priceInINR: "मूल्य (₹)",
    uploadImages: "तस्वीरें और ड्रोन शॉट्स अपलोड करें",
    submitListing: "सूची सुरक्षित रूप से प्रकाशित करें",
    buyTab: "खरीदें",
    rentTab: "किराया",
    landTab: "भूमि",
    commercialTab: "वाणिज्यिक",
    projectsTab: "परियोजनाएं"
  }
};

const INITIAL_PROPERTIES = [
  {
    id: "PROP-101",
    title: "Emerald Heights Luxury 3BHK Apartment",
    category: "Apartment",
    type: "Buy",
    city: "Chennai",
    locality: "Velachery",
    price: 12500000,
    priceFormatted: "₹ 1.25 Cr",
    bedrooms: 3,
    bathrooms: 3,
    areaSqFt: 1850,
    featured: true,
    verified: true,
    image: "https://images.unsplash.com/photo-1545324418-cc1a3fa10c00?auto=format&fit=crop&w=800&q=80",
    droneShot: "https://images.unsplash.com/photo-1512917774080-9991f1c4c750?auto=format&fit=crop&w=800&q=80",
    description: "Ultra-luxurious 3BHK apartment with modular kitchen, wooden flooring, panoramic city views, and top-tier clubhouse amenities.",
    ownerName: "Rajesh Kumar (Direct Owner)",
    contact: "+91 98401 23456",
    aiSummary: "High appreciation zone (+14% YoY). Near IT parks and metro station. Ideal for tech professionals and families.",
    surveyNumber: "SRV-402/1A",
    soilType: "Clay Loam",
    waterSource: "Municipal & Borewell",
    legalClearTitle: "Approved by CMDA / RERA Registered",
    boundaryFencing: "Gated Community Wall",
    listingType: "Owner Listing"
  },
  {
    id: "PROP-102",
    title: "Green Valley Agricultural & Farm Land",
    category: "Agricultural",
    type: "Land",
    city: "Coimbatore",
    locality: "Pollachi Highway",
    price: 4500000,
    priceFormatted: "₹ 45 Lakhs",
    bedrooms: 0,
    bathrooms: 0,
    areaSqFt: 21780, // 0.5 Acre
    featured: true,
    verified: true,
    image: "https://images.unsplash.com/photo-1500382017468-9049fed747ef?auto=format&fit=crop&w=800&q=80",
    droneShot: "https://images.unsplash.com/photo-1599809275151-54b9d034a742?auto=format&fit=crop&w=800&q=80",
    description: "Fertile agricultural land with 50 yielding coconut trees, drip irrigation setup, 3-phase electricity connection, and direct tar-road access.",
    ownerName: "Murugan G (Landowner)",
    contact: "+91 97890 87654",
    aiSummary: "Excellent soil fertility rating. High potential for organic farming or farmhouse resort conversion. Clear pattas.",
    surveyNumber: "SF No. 112/2B",
    soilType: "Red Sandy Loam",
    waterSource: "Open Agricultural Well & Borewell (High yield)",
    legalClearTitle: "Patta Clean, Single Owner Ancestral Land",
    boundaryFencing: "Barbed wire fencing with gate",
    listingType: "Direct Landowner"
  },
  {
    id: "PROP-103",
    title: "Prime Residential Plot in Gated Enclave",
    category: "Plot",
    type: "Land",
    city: "Bengaluru",
    locality: "Devanahalli",
    price: 6800000,
    priceFormatted: "₹ 68 Lakhs",
    bedrooms: 0,
    bathrooms: 0,
    areaSqFt: 2400, // 30x40
    featured: true,
    verified: true,
    image: "https://images.unsplash.com/photo-1524758631624-e2822e304c36?auto=format&fit=crop&w=800&q=80",
    droneShot: "https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=800&q=80",
    description: "BMRDA approved East-facing residential plot in a ready-to-construct gated layout with underground cabling, parks, and 40ft wide blacktop roads.",
    ownerName: "Srinivas Rao (Authorized Agent)",
    contact: "+91 99001 11223",
    aiSummary: "Located just 15 mins from Bengaluru International Airport. High ROI projected due to upcoming aerospace SEZ expansion.",
    surveyNumber: "Plot No. 44, Sy 89",
    soilType: "Hard Red Soil",
    waterSource: "Cauvery Water Pipeline + Overhead Tank",
    legalClearTitle: "A-Khata Clear Title with Bank Loan Eligibility",
    boundaryFencing: "Compound wall across entire layout",
    listingType: "Builder / Developer"
  },
  {
    id: "PROP-104",
    title: "Skyline Commercial Retail Space",
    category: "Commercial",
    type: "Rent",
    city: "Hyderabad",
    locality: "HITECH City",
    price: 150000,
    priceFormatted: "₹ 1.5 Lakhs/mo",
    bedrooms: 0,
    bathrooms: 2,
    areaSqFt: 1500,
    featured: false,
    verified: true,
    image: "https://images.unsplash.com/photo-1497366216548-37526070297c?auto=format&fit=crop&w=800&q=80",
    droneShot: "https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?auto=format&fit=crop&w=800&q=80",
    description: "Grade-A glass façade commercial showroom / office space on main thoroughfare with 100% power backup, high footfall, and basement parking.",
    ownerName: "Anand Verma (Commercial Broker)",
    contact: "+91 91234 56789",
    aiSummary: "High footfall commercial corridor. Zero vacancy zone. Ready for immediate fit-outs.",
    surveyNumber: "Commercial Unit 302",
    soilType: "RCC Foundation",
    waterSource: "Municipal 24/7 Supply",
    legalClearTitle: "Commercial Occupancy Certificate (OC) Issued",
    boundaryFencing: "Security Guarded Glass Tower",
    listingType: "Broker / Channel Partner"
  }
];

export default function App() {
  const [lang, setLang] = useState('en');
  const [theme, setTheme] = useState('dark');
  const [activeTab, setActiveTab] = useState('home');
  const [searchQuery, setSearchQuery] = useState('');
  const [selectedCategory, setSelectedCategory] = useState('All');
  const [selectedType, setSelectedType] = useState('All');
  const [selectedCity, setSelectedCity] = useState('All');
  const [maxPrice, setMaxPrice] = useState(50000000);
  
  // Modals & User state
  const [showAuthModal, setShowAuthModal] = useState(false);
  const [authMode, setAuthMode] = useState('login'); // login or signup
  const [currentUser, setCurrentUser] = useState(null);
  const [showTrialModal, setShowTrialModal] = useState(false);
  const [showPricingModal, setShowPricingModal] = useState(false);
  const [showAIModal, setShowAIModal] = useState(false);
  const [selectedProperty, setSelectedProperty] = useState(null);
  const [showAddPropertyModal, setShowAddPropertyModal] = useState(false);

  // AI Chat state
  const [aiChatMessages, setAiChatMessages] = useState([
    { sender: 'ai', text: "Namaste! I am Ninja AI, your real estate & land investment assistant. How can I help you find properties, verify survey records, or estimate valuations today?" }
  ]);
  const [aiInput, setAiInput] = useState('');

  // Seller Dashboard state
  const [propertiesList, setPropertiesList] = useState(INITIAL_PROPERTIES);
  const [newPropForm, setNewPropForm] = useState({
    title: '',
    category: 'Apartment',
    type: 'Buy',
    city: 'Chennai',
    locality: '',
    price: '',
    areaSqFt: '',
    surveyNumber: '',
    soilType: '',
    waterSource: '',
    legalClearTitle: 'Clear Title / Approved',
    boundaryFencing: 'Gated / Fenced',
    description: '',
    ownerName: '',
    contact: '',
    image: 'https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?auto=format&fit=crop&w=800&q=80',
    droneShot: 'https://images.unsplash.com/photo-1512917774080-9991f1c4c750?auto=format&fit=crop&w=800&q=80'
  });

  // Theme effect
  useEffect(() => {
    if (theme === 'dark') {
      document.documentElement.classList.add('dark');
    } else {
      document.documentElement.classList.remove('dark');
    }
  }, [theme]);

  const t = (key) => {
    return TRANSLATIONS[lang]?.[key] || TRANSLATIONS['en'][key] || key;
  };

  const isRtl = lang === 'ar' || lang === 'urdu';

  const handleAISubmit = (e) => {
    e.preventDefault();
    if (!aiInput.trim()) return;
    const userMsg = aiInput;
    setAiChatMessages(prev => [...prev, { sender: 'user', text: userMsg }]);
    setAiInput('');

    setTimeout(() => {
      let reply = "I analyzed regional market trends for your query. Prices in this micro-market have appreciated by 11.2% over the last 12 months. Would you like me to connect you with verified direct sellers?";
      if (userMsg.toLowerCase().includes('land') || userMsg.toLowerCase().includes('plot')) {
        reply = "For land and agricultural plots, always verify Patta transfer status, FMB sketch, and encumbrance certificate (EC). I found 3 verified land listings matching your criteria.";
      } else if (userMsg.toLowerCase().includes('price') || userMsg.toLowerCase().includes('budget')) {
        reply = "Based on current RBI rate cycles and market data, properties priced between ₹50L - ₹1.5Cr in tier-1 corridors offer the best rental yields.";
      }
      setAiChatMessages(prev => [...prev, { sender: 'ai', text: reply }]);
    }, 1000);
  };

  const handleAddNewPropertySubmit = (e) => {
    e.preventDefault();
    const created = {
      id: `PROP-${Date.now().toString().slice(-4)}`,
      ...newPropForm,
      price: Number(newPropForm.price),
      priceFormatted: `₹ ${(Number(newPropForm.price) / 100000).toFixed(1)} Lakhs`,
      bedrooms: Number(newPropForm.category) === 'Apartment' || Number(newPropForm.category) === 'Villa' ? 3 : 0,
      bathrooms: 2,
      areaSqFt: Number(newPropForm.areaSqFt),
      featured: true,
      verified: true,
      aiSummary: "Newly listed with verified documents & direct owner pricing. High demand expected."
    };
    setPropertiesList([created, ...propertiesList]);
    setShowAddPropertyModal(false);
    alert("Property listed successfully! Your 15-day free trial visibility boost is now active.");
  };

  return (
    <div className={`min-h-screen font-sans ${theme === 'dark' ? 'bg-slate-950 text-slate-100' : 'bg-slate-50 text-slate-900'} ${isRtl ? 'rtl' : 'ltr'}`}>
      
      {}
      <div className="bg-gradient-to-r from-indigo-600 via-purple-600 to-pink-600 text-white text-xs md:text-sm py-2 px-4 text-center font-medium flex items-center justify-center gap-2 shadow-inner">
        <Sparkles className="w-4 h-4 animate-spin" />
        <span>{t('freeTrialBanner')}</span>
        <button 
          onClick={() => setShowTrialModal(true)}
          className="ml-3 bg-white text-indigo-900 px-3 py-0.5 rounded-full text-xs font-bold shadow hover:bg-slate-100 transition"
        >
          Activate Trial
        </button>
      </div>

      {}
      <header className={`sticky top-0 z-40 backdrop-blur-md border-b ${theme === 'dark' ? 'bg-slate-900/80 border-slate-800' : 'bg-white/80 border-slate-200'}`}>
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
          
          {/* Logo & Badges */}
          <div className="flex items-center gap-3 cursor-pointer" onClick={() => setActiveTab('home')}>
            <div className="w-12 h-12 rounded-2xl bg-gradient-to-tr from-indigo-600 to-violet-500 flex items-center justify-center shadow-lg shadow-indigo-500/30 text-white font-black text-xl">
              NE
            </div>
            <div>
              <div className="flex items-center gap-2">
                <span className="font-extrabold text-lg tracking-wider bg-clip-text text-transparent bg-gradient-to-r from-indigo-400 to-purple-400">
                  {t('brand')}
                </span>
                <span className="bg-indigo-500/20 text-indigo-400 text-[10px] px-2 py-0.5 rounded-full font-bold border border-indigo-500/30 flex items-center gap-1">
                  <Shield className="w-3 h-3 text-emerald-400" /> CREATOR SAAS
                </span>
              </div>
              <p className="text-[11px] text-slate-400">Support: vviky966@gmail.com</p>
            </div>
          </div>

          {/* Navigation Links */}
          <nav className="hidden lg:flex items-center gap-6 font-medium text-sm">
            {[
              { id: 'home', label: t('navHome'), icon: Home },
              { id: 'search', label: t('navBuy'), icon: Search },
              { id: 'land', label: t('navLand'), icon: MapPin },
              { id: 'projects', label: t('navProjects'), icon: Layers },
              { id: 'dashboard', label: t('navSell'), icon: PlusCircle },
              { id: 'ai-assistant', label: t('navAI'), icon: Sparkles },
              { id: 'pricing', label: t('navPremium'), icon: Zap },
            ].map((item) => {
              const Icon = item.icon;
              return (
                <button
                  key={item.id}
                  onClick={() => setActiveTab(item.id)}
                  className={`flex items-center gap-1.5 transition py-1 px-2 rounded-lg ${activeTab === item.id ? 'text-indigo-400 bg-indigo-500/10 font-semibold' : 'text-slate-400 hover:text-slate-200'}`}
                >
                  <Icon className="w-4 h-4" />
                  {item.label}
                </button>
              );
            })}
          </nav>

          {/* Right Action Controls: Language, Theme, Auth */}
          <div className="flex items-center gap-3">
            
            {/* Language Selector */}
            <div className="relative">
              <select
                value={lang}
                onChange={(e) => setLang(e.target.value)}
                className={`text-xs font-semibold py-1.5 px-3 rounded-lg border outline-none cursor-pointer ${theme === 'dark' ? 'bg-slate-800 border-slate-700 text-slate-200' : 'bg-white border-slate-300 text-slate-700'}`}
              >
                <option value="en">English (EN)</option>
                <option value="ta">தமிழ் (Tamil)</option>
                <option value="hi">हिन्दी (Hindi)</option>
                <option value="ar">العربية (Arabic)</option>
                <option value="es">Español (Spanish)</option>
                <option value="fr">Français (French)</option>
              </select>
            </div>

            {/* Theme Toggle */}
            <button
              onClick={() => setTheme(theme === 'dark' ? 'light' : 'dark')}
              className={`p-2 rounded-lg border transition ${theme === 'dark' ? 'bg-slate-800 border-slate-700 text-amber-400' : 'bg-white border-slate-300 text-slate-700'}`}
            >
              {theme === 'dark' ? <Sun className="w-4 h-4" /> : <Moon className="w-4 h-4" />}
            </button>

            {/* Auth Buttons */}
            {currentUser ? (
              <div className="flex items-center gap-2 bg-indigo-600/20 border border-indigo-500/30 px-3 py-1.5 rounded-lg">
                <User className="w-4 h-4 text-indigo-400" />
                <span className="text-xs font-bold text-indigo-300">{currentUser.name}</span>
                <button onClick={() => setCurrentUser(null)} className="text-xs text-slate-400 hover:text-white ml-2">Logout</button>
              </div>
            ) : (
              <div className="flex items-center gap-2">
                <button
                  onClick={() => { setAuthMode('login'); setShowAuthModal(true); }}
                  className={`text-xs font-bold px-3 py-2 rounded-lg border transition ${theme === 'dark' ? 'border-slate-700 hover:bg-slate-800' : 'border-slate-300 hover:bg-slate-100'}`}
                >
                  {t('login')}
                </button>
                <button
                  onClick={() => { setAuthMode('signup'); setShowAuthModal(true); }}
                  className="text-xs font-bold px-4 py-2 rounded-lg bg-gradient-to-r from-indigo-600 to-violet-600 text-white shadow-lg shadow-indigo-600/30 hover:opacity-95 transition"
                >
                  {t('createAccount')}
                </button>
              </div>
            )}
          </div>

        </div>
      </header>

      {}
      <main>
        
        {/* --- HOME PAGE VIEW --- */}
        {activeTab === 'home' && (
          <div className="space-y-16 pb-20">
            
            {/* Hero Section */}
            <section className="relative overflow-hidden pt-20 pb-28 px-4 sm:px-6 lg:px-8 text-center bg-gradient-to-b from-indigo-950/40 via-slate-900/20 to-transparent">
              <div className="max-w-4xl mx-auto space-y-6">
                
                <div className="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-indigo-500/10 border border-indigo-500/30 text-indigo-300 text-xs font-bold">
                  <Sparkles className="w-4 h-4 text-indigo-400" />
                  <span>AI-Powered Real Estate & Marketplace SaaS</span>
                </div>

                <h1 className="text-4xl sm:text-6xl font-black tracking-tight leading-none bg-clip-text text-transparent bg-gradient-to-r from-white via-indigo-100 to-slate-400">
                  {t('tagline')}
                </h1>

                <p className="text-base sm:text-xl text-slate-400 max-w-2xl mx-auto font-normal">
                  {t('subheading')}
                </p>

                {/* Advanced Search Card */}
                <div className={`mt-8 p-4 sm:p-6 rounded-3xl border shadow-2xl backdrop-blur-md max-w-3xl mx-auto ${theme === 'dark' ? 'bg-slate-900/90 border-slate-800' : 'bg-white border-slate-200'}`}>
                  
                  {/* Category Tabs */}
                  <div className="flex flex-wrap gap-2 mb-4 justify-center sm:justify-start border-b pb-3 border-slate-800">
                    {[
                      { id: 'All', label: 'All Properties' },
                      { id: 'Buy', label: t('buyTab') },
                      { id: 'Rent', label: t('rentTab') },
                      { id: 'Land', label: t('landTab') },
                      { id: 'Commercial', label: t('commercialTab') },
                    ].map(tab => (
                      <button
                        key={tab.id}
                        onClick={() => setSelectedType(tab.id)}
                        className={`text-xs font-bold px-4 py-2 rounded-xl transition ${selectedType === tab.id ? 'bg-indigo-600 text-white shadow-lg shadow-indigo-600/30' : 'bg-slate-800/50 text-slate-400 hover:text-white'}`}
                      >
                        {tab.label}
                      </button>
                    ))}
                  </div>

                  {/* Input Search Grid */}
                  <div className="grid grid-cols-1 sm:grid-cols-3 gap-3">
                    <div className="flex items-center gap-2 px-3 py-3 rounded-xl bg-slate-800/40 border border-slate-700/60">
                      <MapPin className="w-5 h-5 text-indigo-400" />
                      <input 
                        type="text" 
                        placeholder={t('searchPlaceholder')}
                        value={searchQuery}
                        onChange={(e) => setSearchQuery(e.target.value)}
                        className="bg-transparent border-none outline-none text-sm w-full text-white placeholder-slate-500"
                      />
                    </div>

                    <div className="flex items-center gap-2 px-3 py-3 rounded-xl bg-slate-800/40 border border-slate-700/60">
                      <Building2 className="w-5 h-5 text-indigo-400" />
                      <select 
                        value={selectedCategory} 
                        onChange={(e) => setSelectedCategory(e.target.value)}
                        className="bg-transparent border-none outline-none text-sm w-full text-slate-300 cursor-pointer"
                      >
                        <option value="All" className="bg-slate-900">All Categories</option>
                        <option value="Apartment" className="bg-slate-900">Apartment</option>
                        <option value="Villa" className="bg-slate-900">Villa</option>
                        <option value="Agricultural" className="bg-slate-900">Agricultural Land</option>
                        <option value="Plot" className="bg-slate-900">Residential Plot</option>
                        <option value="Commercial" className="bg-slate-900">Commercial Space</option>
                      </select>
                    </div>

                    <button 
                      onClick={() => setActiveTab('search')}
                      className="w-full py-3 px-6 rounded-xl bg-gradient-to-r from-indigo-600 to-violet-600 hover:from-indigo-500 hover:to-violet-500 text-white font-bold text-sm shadow-lg shadow-indigo-600/40 flex items-center justify-center gap-2 transition transform active:scale-95"
                    >
                      <Search className="w-4 h-4" />
                      <span>{t('searchBtn')}</span>
                    </button>
                  </div>

                  {/* AI Quick Assistant Trigger */}
                  <div className="mt-4 pt-4 border-t border-slate-800/80 flex items-center justify-between text-xs text-slate-400">
                    <span className="flex items-center gap-1.5">
                      <Sparkles className="w-4 h-4 text-purple-400" />
                      Need personalized recommendation or survey verification?
                    </span>
                    <button 
                      onClick={() => setShowAIModal(true)}
                      className="text-indigo-400 font-bold hover:underline flex items-center gap-1"
                    >
                      {t('askAI')} &rarr;
                    </button>
                  </div>

                </div>

                {/* CTA Buttons */}
                <div className="flex flex-wrap items-center justify-center gap-4 pt-6">
                  <button 
                    onClick={() => setShowTrialModal(true)}
                    className="px-8 py-4 rounded-2xl bg-gradient-to-r from-indigo-600 to-purple-600 text-white font-extrabold text-sm shadow-xl shadow-indigo-500/20 hover:scale-105 transition"
                  >
                    {t('startFree')} (15 Days Trial)
                  </button>
                  <button 
                    onClick={() => setActiveTab('search')}
                    className={`px-8 py-4 rounded-2xl border font-extrabold text-sm transition ${theme === 'dark' ? 'border-slate-700 hover:bg-slate-800 text-white' : 'border-slate-300 hover:bg-slate-100 text-slate-800'}`}
                  >
                    {t('exploreProps')}
                  </button>
                </div>

              </div>
            </section>

            {/* Featured Properties & Lands Grid */}
            <section className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
              <div className="flex items-center justify-between mb-8">
                <div>
                  <h2 className="text-2xl font-black">Featured Properties & Verified Lands</h2>
                  <p className="text-sm text-slate-400">Direct owner listings with clear legal titles and AI valuation.</p>
                </div>
                <button onClick={() => setActiveTab('search')} className="text-xs font-bold text-indigo-400 hover:underline flex items-center gap-1">
                  View All Listings &rarr;
                </button>
              </div>

              <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                {propertiesList.map(prop => (
                  <div 
                    key={prop.id}
                    onClick={() => setSelectedProperty(prop)}
                    className={`group rounded-3xl border overflow-hidden cursor-pointer transition hover:-translate-y-1 hover:shadow-2xl ${theme === 'dark' ? 'bg-slate-900 border-slate-800 hover:border-indigo-500/50' : 'bg-white border-slate-200 hover:border-indigo-500'}`}
                  >
                    <div className="relative h-48 overflow-hidden">
                      <img 
                        src={prop.image} 
                        alt={prop.title} 
                        className="w-full h-full object-cover group-hover:scale-110 transition duration-500" 
                      />
                      <div className="absolute top-3 left-3 flex gap-2">
                        <span className="bg-indigo-600/90 backdrop-blur-md text-white text-[10px] font-bold px-2.5 py-1 rounded-full shadow">
                          {prop.category}
                        </span>
                        {prop.verified && (
                          <span className="bg-emerald-600/90 backdrop-blur-md text-white text-[10px] font-bold px-2 py-1 rounded-full flex items-center gap-1 shadow">
                            <CheckCircle2 className="w-3 h-3" /> Verified
                          </span>
                        )}
                      </div>
                      <div className="absolute bottom-3 right-3 bg-slate-950/80 backdrop-blur-md text-white text-xs font-black px-3 py-1 rounded-xl">
                        {prop.priceFormatted}
                      </div>
                    </div>

                    <div className="p-4 space-y-3">
                      <h3 className="font-bold text-base line-clamp-1 group-hover:text-indigo-400 transition">
                        {prop.title}
                      </h3>
                      <p className="text-xs text-slate-400 flex items-center gap-1">
                        <MapPin className="w-3.5 h-3.5 text-indigo-400" />
                        {prop.locality}, {prop.city}
                      </p>

                      {/* Land & Plot Specific Details if applicable */}
                      {prop.surveyNumber && (
                        <div className="bg-slate-800/40 p-2 rounded-xl text-[11px] space-y-1 border border-slate-700/50">
                          <div className="flex justify-between">
                            <span className="text-slate-400">Survey No:</span>
                            <span className="font-semibold text-indigo-300">{prop.surveyNumber}</span>
                          </div>
                          <div className="flex justify-between">
                            <span className="text-slate-400">Soil/Title:</span>
                            <span className="font-semibold text-emerald-400">{prop.soilType}</span>
                          </div>
                        </div>
                      )}

                      <div className="pt-2 border-t border-slate-800 flex items-center justify-between text-xs">
                        <span className="text-slate-400">{prop.ownerName}</span>
                        <span className="text-indigo-400 font-bold flex items-center gap-1">
                          View Details &rarr;
                        </span>
                      </div>
                    </div>
                  </div>
                ))}
              </div>
            </section>

          </div>
        )}

        {/* --- PROPERTY SEARCH & MARKETPLACE VIEW --- */}
        {activeTab === 'search' && (
          <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10 space-y-8">
            <div className="flex flex-col md:flex-row items-start md:items-center justify-between gap-4 bg-slate-900 p-6 rounded-3xl border border-slate-800">
              <div>
                <h1 className="text-2xl font-black">Property & Land Marketplace</h1>
                <p className="text-xs text-slate-400">Explore verified apartments, villas, agricultural lands and commercial spaces across India.</p>
              </div>
              <div className="flex items-center gap-3">
                <button onClick={() => setShowAddPropertyModal(true)} className="px-4 py-2.5 rounded-xl bg-indigo-600 hover:bg-indigo-500 text-white text-xs font-bold flex items-center gap-2">
                  <PlusCircle className="w-4 h-4" /> {t('addNewProperty')}
                </button>
              </div>
            </div>

            {/* Filters Row */}
            <div className="grid grid-cols-1 sm:grid-cols-4 gap-4">
              <input 
                type="text" 
                placeholder="Search location, title, survey no..." 
                value={searchQuery}
                onChange={(e) => setSearchQuery(e.target.value)}
                className="px-4 py-3 rounded-xl bg-slate-900 border border-slate-800 text-sm text-white"
              />
              <select 
                value={selectedCategory} 
                onChange={(e) => setSelectedCategory(e.target.value)}
                className="px-4 py-3 rounded-xl bg-slate-900 border border-slate-800 text-sm text-slate-300"
              >
                <option value="All">All Categories</option>
                <option value="Apartment">Apartment</option>
                <option value="Villa">Villa</option>
                <option value="Agricultural">Agricultural Land</option>
                <option value="Plot">Plot</option>
                <option value="Commercial">Commercial</option>
              </select>
              <select 
                value={selectedCity} 
                onChange={(e) => setSelectedCity(e.target.value)}
                className="px-4 py-3 rounded-xl bg-slate-900 border border-slate-800 text-sm text-slate-300"
              >
                <option value="All">All Cities</option>
                <option value="Chennai">Chennai</option>
                <option value="Coimbatore">Coimbatore</option>
                <option value="Bengaluru">Bengaluru</option>
                <option value="Hyderabad">Hyderabad</option>
              </select>
              <div className="flex items-center justify-between px-4 py-3 rounded-xl bg-slate-900 border border-slate-800 text-sm text-slate-300">
                <span>Max Price: ₹{(maxPrice/10000000).toFixed(1)} Cr</span>
                <input 
                  type="range" 
                  min="1000000" 
                  max="50000000" 
                  step="1000000"
                  value={maxPrice}
                  onChange={(e) => setMaxPrice(Number(e.target.value))}
                  className="accent-indigo-500"
                />
              </div>
            </div>

            {/* Listings Grid */}
            <div className="grid grid-cols-1 md:grid-cols-3 gap-6">
              {propertiesList
                .filter(p => selectedCategory === 'All' || p.category === selectedCategory)
                .filter(p => selectedCity === 'All' || p.city === selectedCity)
                .filter(p => p.price <= maxPrice)
                .filter(p => p.title.toLowerCase().includes(searchQuery.toLowerCase()) || p.locality.toLowerCase().includes(searchQuery.toLowerCase()))
                .map(prop => (
                  <div 
                    key={prop.id}
                    onClick={() => setSelectedProperty(prop)}
                    className="bg-slate-900 border border-slate-800 rounded-3xl overflow-hidden cursor-pointer hover:border-indigo-500 transition shadow-xl"
                  >
                    <div className="relative h-52">
                      <img src={prop.image} alt={prop.title} className="w-full h-full object-cover" />
                      <div className="absolute top-3 left-3 bg-indigo-600 text-white text-[10px] font-bold px-3 py-1 rounded-full">
                        {prop.category}
                      </div>
                      <div className="absolute bottom-3 right-3 bg-slate-950 text-white font-black text-sm px-3 py-1 rounded-xl">
                        {prop.priceFormatted}
                      </div>
                    </div>
                    <div className="p-5 space-y-3">
                      <h3 className="font-bold text-lg">{prop.title}</h3>
                      <p className="text-xs text-slate-400 flex items-center gap-1">
                        <MapPin className="w-4 h-4 text-indigo-400" /> {prop.locality}, {prop.city}
                      </p>
                      {prop.surveyNumber && (
                        <div className="bg-slate-950 p-3 rounded-xl text-xs space-y-1 border border-slate-800">
                          <div className="flex justify-between"><span className="text-slate-400">Survey No:</span> <span className="font-bold text-indigo-400">{prop.surveyNumber}</span></div>
                          <div className="flex justify-between"><span className="text-slate-400">Soil:</span> <span className="font-bold text-emerald-400">{prop.soilType}</span></div>
                          <div className="flex justify-between"><span className="text-slate-400">Water:</span> <span className="font-bold text-cyan-400">{prop.waterSource}</span></div>
                        </div>
                      )}
                      <div className="pt-3 border-t border-slate-800 flex items-center justify-between text-xs">
                        <span className="text-slate-400">Seller: {prop.ownerName}</span>
                        <span className="text-indigo-400 font-bold">Contact Seller &rarr;</span>
                      </div>
                    </div>
                  </div>
              ))}
            </div>
          </div>
        )}

        {/* --- LAND & PLOTS MARKETPLACE VIEW --- */}
        {activeTab === 'land' && (
          <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10 space-y-8">
            <div className="bg-gradient-to-r from-emerald-900/40 to-slate-900 p-8 rounded-3xl border border-emerald-500/30">
              <h1 className="text-3xl font-black text-emerald-300">Agricultural & Land Marketplace</h1>
              <p className="text-sm text-slate-300 mt-2">Verified land parcels with FMB sketches, survey records, soil quality reports, and direct landowner contacts.</p>
            </div>

            <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
              {propertiesList.filter(p => p.category === 'Agricultural' || p.category === 'Plot').map(prop => (
                <div key={prop.id} onClick={() => setSelectedProperty(prop)} className="bg-slate-900 border border-slate-800 rounded-3xl overflow-hidden cursor-pointer hover:border-emerald-500 transition">
                  <div className="relative h-48">
                    <img src={prop.droneShot} alt={prop.title} className="w-full h-full object-cover" />
                    <div className="absolute top-3 left-3 bg-emerald-600 text-white text-[10px] font-bold px-3 py-1 rounded-full">
                      Land Parcel / Plot
                    </div>
                    <div className="absolute bottom-3 right-3 bg-slate-950 text-white font-black text-sm px-3 py-1 rounded-xl">
                      {prop.priceFormatted}
                    </div>
                  </div>
                  <div className="p-5 space-y-3">
                    <h3 className="font-bold text-lg">{prop.title}</h3>
                    <p className="text-xs text-slate-400 flex items-center gap-1"><MapPin className="w-4 h-4 text-emerald-400" /> {prop.locality}, {prop.city}</p>
                    <div className="bg-slate-950 p-3 rounded-xl text-xs space-y-1.5 border border-slate-800">
                      <div className="flex justify-between"><span className="text-slate-400">Survey No:</span> <span className="font-bold text-emerald-300">{prop.surveyNumber}</span></div>
                      <div className="flex justify-between"><span className="text-slate-400">Soil Type:</span> <span className="font-semibold text-slate-200">{prop.soilType}</span></div>
                      <div className="flex justify-between"><span className="text-slate-400">Water Source:</span> <span className="font-semibold text-cyan-300">{prop.waterSource}</span></div>
                      <div className="flex justify-between"><span className="text-slate-400">Legal Title:</span> <span className="font-semibold text-emerald-400">{prop.legalClearTitle}</span></div>
                    </div>
                    <button className="w-full py-2.5 rounded-xl bg-emerald-600/20 text-emerald-400 font-bold text-xs border border-emerald-500/30 hover:bg-emerald-600/30 transition">
                      View Drone Tour & Land Documents
                    </button>
                  </div>
                </div>
              ))}
            </div>
          </div>
        )}

        {/* --- SELLER & LANDOWNER DASHBOARD --- */}
        {activeTab === 'dashboard' && (
          <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10 space-y-8">
            <div className="flex flex-col md:flex-row items-start md:items-center justify-between gap-4 bg-gradient-to-r from-indigo-950 to-slate-900 p-8 rounded-3xl border border-indigo-500/30">
              <div>
                <span className="bg-indigo-500/20 text-indigo-300 text-xs px-3 py-1 rounded-full font-bold">Creator SaaS Portal</span>
                <h1 className="text-3xl font-black mt-2">{t('dashboardTitle')}</h1>
                <p className="text-xs text-slate-400 mt-1">Manage listings, land survey details, direct buyer leads, and SaaS credit balance.</p>
              </div>
              <button 
                onClick={() => setShowAddPropertyModal(true)}
                className="px-6 py-3 rounded-2xl bg-gradient-to-r from-indigo-600 to-violet-600 text-white font-bold text-sm shadow-lg flex items-center gap-2"
              >
                <PlusCircle className="w-5 h-5" /> {t('addNewProperty')}
              </button>
            </div>

            {/* Dashboard Stats */}
            <div className="grid grid-cols-1 sm:grid-cols-4 gap-6">
              {[
                { title: "Active Listings", count: propertiesList.length, icon: Building2, color: "text-indigo-400" },
                { title: "Captured Leads", count: "48 Leads", icon: User, color: "text-emerald-400" },
                { title: "Available Credits", count: "250 Credits", icon: Zap, color: "text-amber-400" },
                { title: "SaaS Subscription", count: "Pro Broker Active", icon: Shield, color: "text-purple-400" },
              ].map((stat, i) => {
                const Icon = stat.icon;
                return (
                  <div key={i} className="bg-slate-900 border border-slate-800 p-6 rounded-3xl space-y-3">
                    <div className="flex items-center justify-between">
                      <span className="text-xs text-slate-400 font-medium">{stat.title}</span>
                      <Icon className={`w-5 h-5 ${stat.color}`} />
                    </div>
                    <div className="text-2xl font-black">{stat.count}</div>
                  </div>
                );
              })}
            </div>

            {/* My Active Listings Table */}
            <div className="bg-slate-900 border border-slate-800 rounded-3xl p-6 space-y-6">
              <h2 className="text-xl font-bold">{t('myListings')}</h2>
              <div className="overflow-x-auto">
                <table className="w-full text-left text-xs">
                  <thead>
                    <tr className="border-b border-slate-800 text-slate-400">
                      <th className="pb-3">Property / Land Title</th>
                      <th className="pb-3">Category</th>
                      <th className="pb-3">Survey No.</th>
                      <th className="pb-3">Price</th>
                      <th className="pb-3">Status</th>
                      <th className="pb-3 text-right">Actions</th>
                    </tr>
                  </thead>
                  <tbody className="divide-y divide-slate-800/60">
                    {propertiesList.map(prop => (
                      <tr key={prop.id} className="hover:bg-slate-800/40 transition">
                        <td className="py-4 font-bold flex items-center gap-3">
                          <img src={prop.image} className="w-10 h-10 rounded-xl object-cover" alt="" />
                          <div>
                            <div>{prop.title}</div>
                            <div className="text-[10px] text-slate-400">{prop.locality}, {prop.city}</div>
                          </div>
                        </td>
                        <td className="py-4"><span className="bg-indigo-500/20 text-indigo-300 px-2.5 py-1 rounded-full font-bold">{prop.category}</span></td>
                        <td className="py-4 font-mono text-emerald-400">{prop.surveyNumber || 'N/A'}</td>
                        <td className="py-4 font-bold">{prop.priceFormatted}</td>
                        <td className="py-4"><span className="text-emerald-400 font-bold flex items-center gap-1"><CheckCircle2 className="w-3.5 h-3.5" /> Boosted</span></td>
                        <td className="py-4 text-right">
                          <button onClick={() => setSelectedProperty(prop)} className="px-3 py-1.5 rounded-lg bg-slate-800 text-indigo-400 font-bold hover:bg-slate-700">View</button>
                        </td>
                      </tr>
                    ))}
                  </tbody>
                </table>
              </div>
            </div>
          </div>
        )}

        {/* --- NINJA AI ASSISTANT VIEW --- */}
        {activeTab === 'ai-assistant' && (
          <div className="max-w-4xl mx-auto px-4 py-10">
            <div className="bg-slate-900 border border-slate-800 rounded-3xl overflow-hidden shadow-2xl flex flex-col h-[700px]">
              
              {/* Chat Header */}
              <div className="p-6 bg-gradient-to-r from-indigo-900 to-purple-900 border-b border-slate-800 flex items-center justify-between">
                <div className="flex items-center gap-3">
                  <div className="w-10 h-10 rounded-2xl bg-indigo-600 flex items-center justify-center text-white font-black shadow">
                    AI
                  </div>
                  <div>
                    <h2 className="font-bold text-base flex items-center gap-2">
                      Ninja AI Property & Land Assistant
                      <span className="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"></span>
                    </h2>
                    <p className="text-xs text-slate-300">Trained on Indian real estate laws, land surveys, pricing & valuation</p>
                  </div>
                </div>
                <span className="text-xs bg-indigo-500/30 px-3 py-1 rounded-full font-bold text-indigo-200">vviky966@gmail.com</span>
              </div>

              {/* Chat Messages */}
              <div className="flex-1 overflow-y-auto p-6 space-y-4">
                {aiChatMessages.map((msg, i) => (
                  <div key={i} className={`flex ${msg.sender === 'user' ? 'justify-end' : 'justify-start'}`}>
                    <div className={`max-w-md p-4 rounded-2xl text-sm ${msg.sender === 'user' ? 'bg-indigo-600 text-white rounded-br-none' : 'bg-slate-800 text-slate-200 rounded-bl-none border border-slate-700/60'}`}>
                      {msg.text}
                    </div>
                  </div>
                ))}
              </div>

              {/* Input Form */}
              <form onSubmit={handleAISubmit} className="p-4 bg-slate-950 border-t border-slate-800 flex items-center gap-3">
                <input 
                  type="text" 
                  placeholder="Ask about survey records, land prices, legal clearance, or property leads..."
                  value={aiInput}
                  onChange={(e) => setAiInput(e.target.value)}
                  className="flex-1 bg-slate-900 border border-slate-800 rounded-2xl px-4 py-3 text-sm text-white outline-none focus:border-indigo-500"
                />
                <button type="submit" className="p-3 rounded-2xl bg-indigo-600 hover:bg-indigo-500 text-white shadow-lg transition">
                  <Send className="w-5 h-5" />
                </button>
              </form>

            </div>
          </div>
        )}

        {/* --- PRICING & SAAS SUBSCRIPTION VIEW --- */}
        {activeTab === 'pricing' && (
          <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 space-y-12">
            <div className="text-center space-y-4 max-w-2xl mx-auto">
              <span className="bg-indigo-500/20 text-indigo-300 text-xs px-3 py-1 rounded-full font-bold">Flexible SaaS Tiers</span>
              <h1 className="text-4xl font-black">Choose Your Growth Plan</h1>
              <p className="text-sm text-slate-400">All plans come with a 15-day free trial. Scale your listings, capture high-intent buyer leads, and leverage AI.</p>
            </div>

            <div className="grid grid-cols-1 md:grid-cols-3 gap-8">
              {[
                { title: "Starter Agent", price: "₹ 1,499 / mo", desc: "For independent agents starting out with AI leads.", badge: "Basic", features: ["10 Active Listings", "Basic AI Assistant", "Standard Visibility", "Email Support"] },
                { title: "Pro Broker", price: "₹ 3,999 / mo", desc: "For professional brokers and landowners needing maximum leads.", badge: "Most Popular", popular: true, features: ["50 Active Listings", "Advanced Land & Survey AI", "Priority Search Placement", "WhatsApp Lead Sync", "Dedicated Support"] },
                { title: "Enterprise Builder", price: "₹ 9,999 / mo", desc: "For large builders and developers with massive project portfolios.", badge: "Ultimate", features: ["Unlimited Listings", "Drone Tour Embeds", "Top Banner Visibility", "API & CRM Integration", "Creator Priority Assistance"] },
              ].map((plan, i) => (
                <div key={i} className={`relative bg-slate-900 rounded-3xl p-8 border flex flex-col justify-between ${plan.popular ? 'border-indigo-500 shadow-2xl shadow-indigo-500/20 ring-2 ring-indigo-500/50' : 'border-slate-800'}`}>
                  {plan.popular && (
                    <span className="absolute -top-3 left-1/2 -translate-x-1/2 bg-gradient-to-r from-indigo-600 to-purple-600 text-white text-[10px] font-black px-3 py-1 rounded-full uppercase">
                      {plan.badge}
                    </span>
                  )}
                  <div className="space-y-4">
                    <h3 className="text-xl font-bold">{plan.title}</h3>
                    <div className="text-3xl font-black text-indigo-400">{plan.price}</div>
                    <p className="text-xs text-slate-400">{plan.desc}</p>
                    <ul className="space-y-3 pt-4 border-t border-slate-800 text-xs">
                      {plan.features.map((feat, idx) => (
                        <li key={idx} className="flex items-center gap-2 text-slate-300">
                          <Check className="w-4 h-4 text-emerald-400" />
                          {feat}
                        </li>
                      ))}
                    </ul>
                  </div>
                  <button 
                    onClick={() => setShowTrialModal(true)}
                    className={`mt-8 w-full py-3.5 rounded-2xl font-bold text-sm transition ${plan.popular ? 'bg-gradient-to-r from-indigo-600 to-violet-600 text-white shadow-lg' : 'bg-slate-800 hover:bg-slate-700 text-white'}`}
                  >
                    Start 15-Day Free Trial
                  </button>
                </div>
              ))}
            </div>
          </div>
        )}

      </main>

      {}
      {selectedProperty && (
        <div className="fixed inset-0 z-50 bg-slate-950/80 backdrop-blur-md flex items-center justify-center p-4">
          <div className="bg-slate-900 border border-slate-800 rounded-3xl max-w-3xl w-full max-h-[90vh] overflow-y-auto p-6 space-y-6 shadow-2xl">
            <div className="flex items-center justify-between border-b border-slate-800 pb-4">
              <h2 className="text-xl font-black">{selectedProperty.title}</h2>
              <button onClick={() => setSelectedProperty(null)} className="p-2 rounded-xl bg-slate-800 text-slate-400 hover:text-white">
                <X className="w-5 h-5" />
              </button>
            </div>

            <div className="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <img src={selectedProperty.image} className="w-full h-56 rounded-2xl object-cover" alt="" />
              <img src={selectedProperty.droneShot} className="w-full h-56 rounded-2xl object-cover" alt="" />
            </div>

            <div className="grid grid-cols-2 sm:grid-cols-4 gap-4 bg-slate-950 p-4 rounded-2xl border border-slate-800 text-xs">
              <div><span className="text-slate-400">Category:</span> <div className="font-bold text-white mt-1">{selectedProperty.category}</div></div>
              <div><span className="text-slate-400">Price:</span> <div className="font-bold text-indigo-400 mt-1">{selectedProperty.priceFormatted}</div></div>
              <div><span className="text-slate-400">Area:</span> <div className="font-bold text-white mt-1">{selectedProperty.areaSqFt} Sq.Ft</div></div>
              <div><span className="text-slate-400">City:</span> <div className="font-bold text-white mt-1">{selectedProperty.city}</div></div>
            </div>

            {selectedProperty.surveyNumber && (
              <div className="bg-emerald-950/30 border border-emerald-500/30 p-4 rounded-2xl space-y-2">
                <h4 className="font-bold text-emerald-400 text-sm flex items-center gap-2">
                  <Shield className="w-4 h-4" /> Land & Survey Legal Verification
                </h4>
                <div className="grid grid-cols-1 sm:grid-cols-2 gap-2 text-xs">
                  <div><span className="text-slate-400">Survey No:</span> <span className="text-white font-mono font-bold">{selectedProperty.surveyNumber}</span></div>
                  <div><span className="text-slate-400">Soil Type:</span> <span className="text-white font-semibold">{selectedProperty.soilType}</span></div>
                  <div><span className="text-slate-400">Water Source:</span> <span className="text-cyan-300 font-semibold">{selectedProperty.waterSource}</span></div>
                  <div><span className="text-slate-400">Legal Title:</span> <span className="text-emerald-300 font-semibold">{selectedProperty.legalClearTitle}</span></div>
                </div>
              </div>
            )}

            <div className="space-y-2">
              <h4 className="font-bold text-sm">AI Property Summary</h4>
              <p className="text-xs text-slate-300 bg-slate-950 p-4 rounded-2xl border border-slate-800">{selectedProperty.aiSummary}</p>
            </div>

            <div className="flex items-center justify-between pt-4 border-t border-slate-800">
              <div>
                <div className="text-xs text-slate-400">Listed by: {selectedProperty.ownerName}</div>
                <div className="text-sm font-bold text-indigo-400">{selectedProperty.contact}</div>
              </div>
              <button 
                onClick={() => alert(`Connection request sent to ${selectedProperty.ownerName}. They will contact you shortly!`)}
                className="px-6 py-3 rounded-xl bg-gradient-to-r from-indigo-600 to-violet-600 text-white text-xs font-bold shadow-lg"
              >
                Contact Seller Directly
              </button>
            </div>
          </div>
        </div>
      )}

      {}
      {showAddPropertyModal && (
        <div className="fixed inset-0 z-50 bg-slate-950/80 backdrop-blur-md flex items-center justify-center p-4">
          <div className="bg-slate-900 border border-slate-800 rounded-3xl max-w-2xl w-full max-h-[90vh] overflow-y-auto p-6 space-y-6 shadow-2xl">
            <div className="flex items-center justify-between border-b border-slate-800 pb-4">
              <h2 className="text-xl font-black">{t('addNewProperty')}</h2>
              <button onClick={() => setShowAddPropertyModal(false)} className="p-2 rounded-xl bg-slate-800 text-slate-400 hover:text-white">
                <X className="w-5 h-5" />
              </button>
            </div>

            <form onSubmit={handleAddNewPropertySubmit} className="space-y-4 text-xs">
              <div className="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label className="text-slate-400 block mb-1 font-bold">Property Title</label>
                  <input 
                    type="text" required
                    placeholder="e.g. 2 Acre Agricultural Land in Pollachi"
                    value={newPropForm.title}
                    onChange={(e) => setNewPropForm({...newPropForm, title: e.target.value})}
                    className="w-full p-3 rounded-xl bg-slate-950 border border-slate-800 text-white"
                  />
                </div>
                <div>
                  <label className="text-slate-400 block mb-1 font-bold">Category</label>
                  <select 
                    value={newPropForm.category}
                    onChange={(e) => setNewPropForm({...newPropForm, category: e.target.value})}
                    className="w-full p-3 rounded-xl bg-slate-950 border border-slate-800 text-white cursor-pointer"
                  >
                    <option value="Apartment">Apartment</option>
                    <option value="Villa">Villa</option>
                    <option value="Agricultural">Agricultural Land</option>
                    <option value="Plot">Residential Plot</option>
                    <option value="Commercial">Commercial Space</option>
                  </select>
                </div>
              </div>

              <div className="grid grid-cols-1 sm:grid-cols-3 gap-4">
                <div>
                  <label className="text-slate-400 block mb-1 font-bold">City</label>
                  <input 
                    type="text" required placeholder="Chennai / Coimbatore"
                    value={newPropForm.city}
                    onChange={(e) => setNewPropForm({...newPropForm, city: e.target.value})}
                    className="w-full p-3 rounded-xl bg-slate-950 border border-slate-800 text-white"
                  />
                </div>
                <div>
                  <label className="text-slate-400 block mb-1 font-bold">Locality</label>
                  <input 
                    type="text" required placeholder="Velachery / Pollachi Hwy"
                    value={newPropForm.locality}
                    onChange={(e) => setNewPropForm({...newPropForm, locality: e.target.value})}
                    className="w-full p-3 rounded-xl bg-slate-950 border border-slate-800 text-white"
                  />
                </div>
                <div>
                  <label className="text-slate-400 block mb-1 font-bold">Price in INR (₹)</label>
                  <input 
                    type="number" required placeholder="4500000"
                    value={newPropForm.price}
                    onChange={(e) => setNewPropForm({...newPropForm, price: e.target.value})}
                    className="w-full p-3 rounded-xl bg-slate-950 border border-slate-800 text-white"
                  />
                </div>
              </div>

              {/* Land Specific Fields */}
              <div className="bg-slate-950 p-4 rounded-2xl border border-slate-800 space-y-3">
                <div className="font-bold text-emerald-400">Land & Survey Specifics (Optional)</div>
                <div className="grid grid-cols-1 sm:grid-cols-3 gap-3">
                  <div>
                    <label className="text-slate-400 block mb-1">Survey Number</label>
                    <input 
                      type="text" placeholder="SF No. 112/2B"
                      value={newPropForm.surveyNumber}
                      onChange={(e) => setNewPropForm({...newPropForm, surveyNumber: e.target.value})}
                      className="w-full p-2.5 rounded-xl bg-slate-900 border border-slate-800 text-white"
                    />
                  </div>
                  <div>
                    <label className="text-slate-400 block mb-1">Soil Type</label>
                    <input 
                      type="text" placeholder="Red Loam / Clay"
                      value={newPropForm.soilType}
                      onChange={(e) => setNewPropForm({...newPropForm, soilType: e.target.value})}
                      className="w-full p-2.5 rounded-xl bg-slate-900 border border-slate-800 text-white"
                    />
                  </div>
                  <div>
                    <label className="text-slate-400 block mb-1">Water Source</label>
                    <input 
                      type="text" placeholder="Borewell / Open Well"
                      value={newPropForm.waterSource}
                      onChange={(e) => setNewPropForm({...newPropForm, waterSource: e.target.value})}
                      className="w-full p-2.5 rounded-xl bg-slate-900 border border-slate-800 text-white"
                    />
                  </div>
                </div>
              </div>

              <div>
                <label className="text-slate-400 block mb-1 font-bold">Description & Amenities</label>
                <textarea 
                  rows="3" required placeholder="Describe property features..."
                  value={newPropForm.description}
                  onChange={(e) => setNewPropForm({...newPropForm, description: e.target.value})}
                  className="w-full p-3 rounded-xl bg-slate-950 border border-slate-800 text-white"
                />
              </div>

              <div className="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label className="text-slate-400 block mb-1 font-bold">Owner / Agent Name</label>
                  <input 
                    type="text" required placeholder="Murugan G"
                    value={newPropForm.ownerName}
                    onChange={(e) => setNewPropForm({...newPropForm, ownerName: e.target.value})}
                    className="w-full p-3 rounded-xl bg-slate-950 border border-slate-800 text-white"
                  />
                </div>
                <div>
                  <label className="text-slate-400 block mb-1 font-bold">Contact Number</label>
                  <input 
                    type="text" required placeholder="+91 98765 43210"
                    value={newPropForm.contact}
                    onChange={(e) => setNewPropForm({...newPropForm, contact: e.target.value})}
                    className="w-full p-3 rounded-xl bg-slate-950 border border-slate-800 text-white"
                  />
                </div>
              </div>

              <button 
                type="submit"
                className="w-full py-4 rounded-2xl bg-gradient-to-r from-indigo-600 to-violet-600 text-white font-extrabold text-sm shadow-xl"
              >
                {t('submitListing')}
              </button>
            </form>
          </div>
        </div>
      )}

      {}
      <footer className={`border-t py-12 mt-20 ${theme === 'dark' ? 'bg-slate-900 border-slate-800' : 'bg-white border-slate-200'}`}>
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 space-y-8">
          
          <div className="flex flex-col md:flex-row items-center justify-between gap-6">
            <div className="flex items-center gap-3">
              <div className="w-10 h-10 rounded-xl bg-indigo-600 flex items-center justify-center text-white font-black text-lg">
                NE
              </div>
              <div>
                <span className="font-extrabold text-base">{t('brand')}</span>
                <p className="text-xs text-slate-400">Creator Support: <a href="mailto:vviky966@gmail.com" className="text-indigo-400 font-bold underline">vviky966@gmail.com</a></p>
              </div>
            </div>

            <div className="flex flex-wrap gap-6 text-xs font-semibold text-slate-400">
              <button onClick={() => setActiveTab('home')} className="hover:text-white">Home</button>
              <button onClick={() => setActiveTab('search')} className="hover:text-white">Marketplace</button>
              <button onClick={() => setActiveTab('pricing')} className="hover:text-white">Subscription Pricing</button>
              <button onClick={() => setActiveTab('ai-assistant')} className="hover:text-white">Ninja AI Assistant</button>
            </div>
          </div>

          <div className="border-t border-slate-800/80 pt-6 text-xs text-slate-500 text-center leading-relaxed">
            {t('disclaimer')}
          </div>

        </div>
      </footer>

    </div>
  );
}