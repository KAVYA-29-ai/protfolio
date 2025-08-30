{/* Status badge */}
                  <motion.div
                    className={`absolute top-4 right-4 px-3 py-1 rounded-full text-sm font-semibold ${
                      project.status === 'completed' 
                        ? 'bg-green-500/20 text-green-400 border border-green-500/30' 
                        : 'bg-orange-500/20 text-orange-400 border border-orange-500/30'
                    }`}
                    initial={{ scale: 0 }}
                    animate={{ scale: 1 }}
                    transition={{ delay: 0.7, type: "spring" }}
                  >
                    {project.status === 'completed' ? '✅ Complete' : '🔄 In Progress'}
                  </motion.div>

                  {/* Floating particles */}
                  {[...Array(6)].map((_, i) => (
                    <motion.div
                      key={i}
                      className="absolute w-2 h-2 bg-white/30 rounded-full"
                      style={{
                        left: `${20 + i * 12}%`,
                        top: `${30 + (i % 2) * 40}%`,
                      }}
                      animate={{
                        y: [0, -20, 0],
                        opacity: [0.3, 1, 0.3],
                        scale: [1, 1.2, 1],
                      }}
                      transition={{
                        duration: 3,
                        repeat: Infinity,
                        delay: i * 0.2,
                        ease: "easeInOut"
                      }}
                    />
                  ))}
                </div>

                {/* Project content */}
                <div className="p-8">
                  <div className="flex items-center justify-between mb-4">
                    <span className={`px-3 py-1 rounded-full text-xs font-semibold bg-gradient-to-r ${project.color} text-white`}>
                      {project.category}
                    </span>
                    <span className="text-gray-500 text-sm">{project.year}</span>
                  </div>

                  <h3 className="text-2xl font-bold text-white mb-4 group-hover:text-cyan-400 transition-colors">
                    {project.title}
                  </h3>
                  
                  <p className="text-gray-400 mb-6 line-clamp-3 leading-relaxed">
                    {project.description}
                  </p>
                  
                  <div className="flex flex-wrap gap-2 mb-6">
                    {project.tech.slice(0, 4).map((tech, idx) => (
                      <motion.span
                        key={idx}
                        whileHover={{ scale: 1.05 }}
                        className="px-3 py-1 bg-gray-700/50 text-gray-300 text-sm rounded-full border border-gray-600/50 hover:border-cyan-500/50 transition-colors"
                      >
                        {tech}
                      </motion.span>
                    ))}
                    {project.tech.length > 4 && (
                      <span className="px-3 py-1 bg-gray-700/50 text-gray-400 text-sm rounded-full">
                        +{project.tech.length - 4} more
                      </span>
                    )}
                  </div>
                  
                  <div className="flex gap-4">
                    <motion.button
                      whileHover={{ scale: 1.05 }}
                      whileTap={{ scale: 0.95 }}
                      className="flex items-center gap-2 px-4 py-2 bg-cyan-600 text-white rounded-xl hover:bg-cyan-500 transition-colors text-sm font-semibold"
                      onClick={(e) => {
                        e.stopPropagation();
                        window.open(project.github, '_blank');
                      }}
                    >
                      <Github size={16} />
                      Code
                    </motion.button>
                    <motion.button
                      whileHover={{ scale: 1.05 }}
                      whileTap={{ scale: 0.95 }}
                      className="flex items-center gap-2 px-4 py-2 border border-cyan-500/50 text-cyan-400 rounded-xl hover:bg-cyan-500/10 transition-colors text-sm font-semibold"
                      onClick={(e) => {
                        e.stopPropagation();
                        window.open(project.live, '_blank');
                      }}
                    >
                      <ExternalLink size={16} />
                      Live Demo
                    </motion.button>
                  </div>
                </div>

                {/* Hover overlay */}
                <motion.div
                  className="absolute inset-0 bg-gradient-to-t from-cyan-900/20 via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500 pointer-events-none"
                  whileHover={{ opacity: 1 }}
                />
              </motion.div>
            ))}
          </AnimatePresence>
        </motion.div>

        {/* Show more button */}
        <motion.div
          className="text-center mt-16"
          initial={{ opacity: 0, y: 50 }}
          animate={isInView ? { opacity: 1, y: 0 } : {}}
          transition={{ delay: 1.5, duration: 1 }}
        >
          <motion.button
            whileHover={{ 
              scale: 1.05,
              boxShadow: "0 0 40px rgba(6, 182, 212, 0.5)"
            }}
            whileTap={{ scale: 0.95 }}
            className="px-12 py-4 bg-gradient-to-r from-cyan-600 to-purple-600 text-white rounded-full font-bold text-lg hover:from-cyan-500 hover:to-purple-500 transition-all duration-300 flex items-center gap-3 mx-auto"
          >
            <Github size={24} />
            View All Projects on GitHub
            <ArrowRight size={24} />
          </motion.button>
        </motion.div>
      </motion.div>

      {/* Enhanced Project Modal */}
      <AnimatePresence>
        {selectedProject && (
          <motion.div
            initial={{ opacity: 0 }}
            animate={{ opacity: 1 }}
            exit={{ opacity: 0 }}
            className="fixed inset-0 bg-black/90 backdrop-blur-xl z-50 flex items-center justify-center p-4"
            onClick={() => setSelectedProject(null)}
          >
            <motion.div
              initial={{ scale: 0.8, opacity: 0, rotateX: -30 }}
              animate={{ scale: 1, opacity: 1, rotateX: 0 }}
              exit={{ scale: 0.8, opacity: 0, rotateX: 30 }}
              transition={{ type: "spring", stiffness: 300, damping: 30 }}
              className="bg-gray-900/95 backdrop-blur-xl border border-cyan-500/30 rounded-3xl max-w-6xl w-full max-h-[90vh] overflow-auto relative"
              onClick={(e) => e.stopPropagation()}
            >
              {/* Close button */}
              <motion.button
                onClick={() => setSelectedProject(null)}
                whileHover={{ scale: 1.1, rotate: 90 }}
                whileTap={{ scale: 0.9 }}
                className="absolute top-6 right-6 w-12 h-12 bg-gray-800/80 hover:bg-red-500/20 border border-gray-700/50 hover:border-red-500/50 rounded-full flex items-center justify-center text-gray-400 hover:text-red-400 transition-all z-10"
              >
                <X size={24} />
              </motion.button>

              {/* Header section */}
              <div className={`h-80 bg-gradient-to-br ${selectedProject.color} relative overflow-hidden flex items-center justify-center`}>
                <motion.div
                  className="text-9xl opacity-40"
                  animate={{
                    scale: [1, 1.1, 1],
                    rotate: [0, 5, -5, 0],
                  }}
                  transition={{
                    duration: 4,
                    repeat: Infinity,
                    ease: "easeInOut"
                  }}
                >
                  {selectedProject.category === 'AI/ML' ? '🤖' :
                   selectedProject.category === 'Data Analytics' ? '📊' :
                   selectedProject.category === 'IoT' ? '🌐' :
                   selectedProject.category === 'Blockchain' ? '⛓️' : '🚀'}
                </motion.div>

                {/* Floating elements */}
                {[...Array(12)].map((_, i) => (
                  <motion.div
                    key={i}
                    className="absolute w-4 h-4 bg-white/20 rounded-full"
                    style={{
                      left: `${Math.random() * 100}%`,
                      top: `${Math.random() * 100}%`,
                    }}
                    animate={{
                      y: [0, -30, 0],
                      x: [0, Math.random() * 20 - 10, 0],
                      opacity: [0.2, 0.8, 0.2],
                      scale: [1, 1.5, 1],
                    }}
                    transition={{
                      duration: 3,
                      repeat: Infinity,
                      delay: i * 0.2,
                      ease: "easeInOut"
                    }}
                  />
                ))}

                {/* Project title overlay */}
                <div className="absolute bottom-0 left-0 right-0 bg-gradient-to-t from-black/60 to-transparent p-8">
                  <div className="flex items-center gap-4 mb-4">
                    <span className={`px-4 py-2 rounded-full text-sm font-semibold bg-gradient-to-r ${selectedProject.color} text-white`}>
                      {selectedProject.category}
                    </span>
                    <span className="text-white/80">{selectedProject.year}</span>
                    {selectedProject.featured && (
                      <span className="px-3 py-1 bg-yellow-500/20 text-yellow-400 border border-yellow-500/30 rounded-full text-sm font-semibold flex items-center gap-1">
                        <Star size={14} />
                        Featured
                      </span>
                    )}
                  </div>
                  <h3 className="text-4xl font-black text-white mb-2">
                    {selectedProject.title}
                  </h3>
                  <p className="text-xl text-white/90">
                    {selectedProject.description}
                  </p>
                </div>
              </div>

              {/* Content section */}
              <div className="p-8">
                <div className="grid lg:grid-cols-2 gap-12">
                  {/* Left column */}
                  <div className="space-y-8">
                    <div>
                      <h4 className="text-2xl font-bold text-cyan-400 mb-4">Project Overview</h4>
                      <p className="text-gray-300 leading-relaxed text-lg">
                        {selectedProject.longDescription}
                      </p>
                    </div>

                    <div>
                      <h4 className="text-2xl font-bold text-cyan-400 mb-6">Key Statistics</h4>
                      <div className="grid grid-cols-2 gap-4">
                        {selectedProject.preview.stats.map((stat, idx) => (
                          <motion.div
                            key={idx}
                            className="bg-gray-800/50 border border-gray-700/50 rounded-xl p-4 text-center"
                            whileHover={{ scale: 1.05, borderColor: 'rgba(6, 182, 212, 0.5)' }}
                          >
                            <div className="text-2xl font-bold text-white mb-1">
                              {stat.split(' ')[0]}
                            </div>
                            <div className="text-sm text-gray-400">
                              {stat.split(' ').slice(1).join(' ')}
                            </div>
                          </motion.div>
                        ))}
                      </div>
                    </div>

                    <div>
                      <h4 className="text-2xl font-bold text-cyan-400 mb-4">Technologies Used</h4>
                      <div className="flex flex-wrap gap-3">
                        {selectedProject.tech.map((tech, idx) => (
                          <motion.span
                            key={idx}
                            whileHover={{ scale: 1.1 }}
                            className={`px-4 py-2 bg-gradient-to-r ${selectedProject.color} text-white rounded-full text-sm font-semibold`}
                          >
                            {tech}
                          </motion.span>
                        ))}
                      </div>
                    </div>
                  </div>

                  {/* Right column */}
                  <div className="space-y-8">
                    <div>
                      <h4 className="text-2xl font-bold text-cyan-400 mb-4">Key Features</h4>
                      <div className="space-y-3">
                        {selectedProject.preview.features.map((feature, idx) => (
                          <motion.div
                            key={idx}
                            className="flex items-center gap-3"
                            initial={{ opacity: 0, x: 20 }}
                            animate={{ opacity: 1, x: 0 }}
                            transition={{ delay: idx * 0.1 }}
                          >
                            <motion.div
                              whileHover={{ rotate: 360 }}
                              className={`w-6 h-6 rounded-full bg-gradient-to-r ${selectedProject.color} flex items-center justify-center`}
                            >
                              <Sparkles size={12} className="text-white" />
                            </motion.div>
                            <span className="text-gray-300">{feature}</span>
                          </motion.div>
                        ))}
                      </div>
                    </div>

                    <div>
                      <h4 className="text-2xl font-bold text-cyan-400 mb-4">Technical Highlights</h4>
                      <div className="space-y-3">
                        {selectedProject.preview.technologies.map((tech, idx) => (
                          <motion.div
                            key={idx}
                            className="flex items-center gap-3"
                            initial={{ opacity: 0, x: 20 }}
                            animate={{ opacity: 1, x: 0 }}
                            transition={{ delay: idx * 0.1 + 0.5 }}
                          >
                            <motion.div
                              whileHover={{ scale: 1.2 }}
                              className="w-6 h-6 rounded bg-gray-700/50 flex items-center justify-center"
                            >
                              <Code size={12} className="text-cyan-400" />
                            </motion.div>
                            <span className="text-gray-300">{tech}</span>
                          </motion.div>
                        ))}
                      </div>
                    </div>

                    <div className="flex gap-4 pt-4">
                      <motion.a
                        href={selectedProject.github}
                        target="_blank"
                        rel="noopener noreferrer"
                        whileHover={{ scale: 1.05 }}
                        whileTap={{ scale: 0.95 }}
                        className="flex items-center gap-3 px-8 py-4 bg-gradient-to-r from-gray-700 to-gray-800 text-white rounded-xl hover:from-gray-600 hover:to-gray-700 transition-all font-semibold"
                      >
                        <Github size={20} />
                        View Source Code
                      </motion.a>
                      <motion.a
                        href={selectedProject.live}
                        target="_blank"
                        rel="noopener noreferrer"
                        whileHover={{ scale: 1.05 }}
                        whileTap={{ scale: 0.95 }}
                        className={`flex items-center gap-3 px-8 py-4 bg-gradient-to-r ${selectedProject.color} text-white rounded-xl hover:opacity-90 transition-all font-semibold`}
                      >
                        <ExternalLink size={20} />
                        Live Demo
                      </motion.a>
                    </div>
                  </div>
                </div>
              </div>
            </motion.div>
          </motion.div>
        )}
      </AnimatePresence>
    </section>
  );
};

// Ultra-Enhanced Contact Section
const UltraContact = () => {
  const ref = useRef(null);
  const isInView = useInView(ref, { once: true });
  const [formData, setFormData] = useState({ name: '', email: '', message: '' });
  const [isSubmitting, setIsSubmitting] = useState(false);

  const handleSubmit = async (e) => {
    e.preventDefault();
    setIsSubmitting(true);
    // Simulate form submission
    await new Promise(resolve => setTimeout(resolve, 2000));
    setIsSubmitting(false);
    setFormData({ name: '', email: '', message: '' });
  };

  const socialLinks = [
    { icon: Github, label: 'GitHub', href: '#', color: 'from-gray-600 to-gray-800' },
    { icon: Linkedin, label: 'LinkedIn', href: '#', color: 'from-blue-600 to-blue-800' },
    { icon: Twitter, label: 'Twitter', href: '#', color: 'from-cyan-500 to-blue-500' },
    { icon: Instagram, label: 'Instagram', href: '#', color: 'from-pink-500 to-purple-500' },
    { icon: Mail, label: 'Email', href: 'mailto:kavya.rajput@email.com', color: 'from-red-500 to-pink-500' },
  ];

  return (
    <section ref={ref} className="py-32 px-8 lg:px-16 relative overflow-hidden" id="contact">
      {/* Animated background */}
      <div className="absolute inset-0">
        <motion.div
          animate={{
            scale: [1, 1.2, 1],
            rotate: [0, 180, 360],
          }}
          transition={{
            duration: 30,
            repeat: Infinity,
            ease: "linear"
          }}
          className="absolute -top-1/2 -left-1/2 w-full h-full bg-gradient-to-r from-cyan-500/10 via-purple-500/10 to-pink-500/10 rounded-full blur-3xl"
        />
      </div>

      <motion.div
        initial={{ opacity: 0 }}
        animate={isInView ? { opacity: 1 } : {}}
        transition={{ duration: 1 }}
        className="max-w-6xl mx-auto relative z-10"
      >
        <motion.div
          className="text-center mb-20"
          initial={{ opacity: 0, y: 100 }}
          animate={isInView ? { opacity: 1, y: 0 } : {}}
          transition={{ duration: 1, type: "spring" }}
        >
          <motion.h2 
            className="text-6xl lg:text-7xl font-black mb-8 relative inline-block"
          >
            <span className="bg-gradient-to-r from-cyan-400 via-purple-400 to-pink-400 bg-clip-text text-transparent">
              Let's Connect
            </span>
            <motion.div
              className="absolute -inset-4 bg-gradient-to-r from-cyan-500/20 to-purple-500/20 rounded-2xl blur-xl"
              animate={{
                scale: [1, 1.1, 1],
                opacity: [0.3, 0.6, 0.3],
              }}
              transition={{
                duration: 3,
                repeat: Infinity,
                ease: "easeInOut"
              }}
            />
          </motion.h2>
          
          <motion.p
            className="text-2xl text-gray-400 max-w-4xl mx-auto"
            initial={{ opacity: 0, y: 30 }}
            animate={isInView ? { opacity: 1, y: 0 } : {}}
            transition={{ delay: 0.3, duration: 1 }}
          >
            Ready to collaborate on exciting AI/ML projects or discuss opportunities? 
            Let's build the future together!
          </motion.p>
        </motion.div>

        <div className="grid lg:grid-cols-2 gap-16 items-start">
          {/* Left column - Contact info */}
          <motion.div
            initial={{ opacity: 0, x: -100 }}
            animate={isInView ? { opacity: 1, x: 0 } : {}}
            transition={ delay: 0.4, duration: 1 }}
            className="space-y-8"
          >
            {/* Contact cards */}
            <div className="grid gap-6">
              {[
                { icon: Mail, label: 'Email', value: 'kavya.rajput@email.com', color: 'from-red-500 to-pink-500' },
                { icon: Phone, label: 'Phone', value: '+91 XXXXX XXXXX', color: 'from-green-500 to-emerald-500' },
                { icon: MapPin, label: 'Location', value: 'India', color: 'from-blue-500 to-cyan-500' },
                { icon: Globe, label: 'Website', value: 'www.kavyarajput.dev', color: 'from-purple-500 to-pink-500' },
              ].map((contact, index) => (
                <motion.div
                  key={contact.label}
                  whileHover={{ 
                    scale: 1.05, 
                    rotateY: 5,
                    boxShadow: "0 0 30px rgba(6, 182, 212, 0.3)"
                  }}
                  className="bg-gray-800/80 backdrop-blur-sm border border-gray-700/50 rounded-2xl p-6 hover:border-cyan-500/50 transition-all duration-500 group"
                  initial={{ opacity: 0, y: 50 }}
                  animate={isInView ? { opacity: 1, y: 0 } : {}}
                  transition={{ delay: 0.6 + index * 0.1, duration: 0.8 }}
                >
                  <div className="flex items-center gap-4">
                    <motion.div
                      className={`w-14 h-14 rounded-2xl bg-gradient-to-r ${contact.color} flex items-center justify-center group-hover:scale-110 transition-transform duration-300`}
                      whileHover={{ rotate: 360 }}
                      transition={{ duration: 0.6 }}
                    >
                      <contact.icon size={24} className="text-white" />
                    </motion.div>
                    <div>
                      <h3 className="text-xl font-bold text-white mb-1 group-hover:text-cyan-400 transition-colors">
                        {contact.label}
                      </h3>
                      <p className="text-gray-400">{contact.value}</p>
                    </div>
                  </div>
                </motion.div>
              ))}
            </div>

            {/* Social links */}
            <motion.div
              initial={{ opacity: 0, y: 50 }}
              animate={isInView ? { opacity: 1, y: 0 } : {}}
              transition={{ delay: 1, duration: 1 }}
              className="bg-gray-800/80 backdrop-blur-sm border border-gray-700/50 rounded-2xl p-6"
            >
              <h3 className="text-xl font-bold text-white mb-6 text-center">Follow Me</h3>
              <div className="flex justify-center gap-4">
                {socialLinks.map((social, index) => (
                  <motion.a
                    key={social.label}
                    href={social.href}
                    target="_blank"
                    rel="noopener noreferrer"
                    whileHover={{ 
                      scale: 1.2, 
                      rotate: 10,
                      boxShadow: "0 0 20px rgba(6, 182, 212, 0.5)"
                    }}
                    whileTap={{ scale: 0.9 }}
                    className={`w-12 h-12 bg-gradient-to-r ${social.color} rounded-full flex items-center justify-center text-white relative overflow-hidden group`}
                    initial={{ opacity: 0, scale: 0 }}
                    animate={isInView ? { opacity: 1, scale: 1 } : {}}
                    transition={{ delay: 1.2 + index * 0.1, type: "spring" }}
                  >
                    <motion.div
                      className="absolute inset-0 bg-gradient-to-r from-transparent via-white/20 to-transparent"
                      animate={{
                        x: [-50, 50],
                        opacity: [0, 1, 0],
                      }}
                      transition={{
                        duration: 2,
                        repeat: Infinity,
                        delay: index * 0.3,
                        ease: "easeInOut"
                      }}
                    />
                    <social.icon size={20} className="relative z-10" />
                  </motion.a>
                ))}
              </div>
            </motion.div>
          </motion.div>

          {/* Right column - Contact form */}
          <motion.div
            initial={{ opacity: 0, x: 100 }}
            animate={isInView ? { opacity: 1, x: 0 } : {}}
            transition={{ delay: 0.4, duration: 1 }}
            className="bg-gray-800/80 backdrop-blur-sm border border-gray-700/50 rounded-3xl p-8 hover:border-cyan-500/50 transition-all duration-500"
          >
            <h3 className="text-3xl font-bold text-white mb-6 text-center">
              Send Me a Message
            </h3>
            
            <form onSubmit={handleSubmit} className="space-y-6">
              <div>
                <label className="block text-sm font-semibold text-gray-300 mb-2">
                  Your Name
                </label>
                <motion.input
                  whileFocus={{ scale: 1.02, borderColor: '#06b6d4' }}
                  type="text"
                  value={formData.name}
                  onChange={(e) => setFormData({...formData, name: e.target.value})}
                  className="w-full px-4 py-3 bg-gray-900/50 border border-gray-600/50 rounded-xl text-white placeholder-gray-500 focus:outline-none focus:border-cyan-500 transition-all"
                  placeholder="Enter your name"
                  required
                />
              </div>
              
              <div>
                <label className="block text-sm font-semibold text-gray-300 mb-2">
                  Email Address
                </label>
                <motion.input
                  whileFocus={{ scale: 1.02, borderColor: '#06b6d4' }}
                  type="email"
                  value={formData.email}
                  onChange={(e) => setFormData({...formData, email: e.target.value})}
                  className="w-full px-4 py-3 bg-gray-900/50 border border-gray-600/50 rounded-xl text-white placeholder-gray-500 focus:outline-none focus:border-cyan-500 transition-all"
                  placeholder="Enter your email"
                  required
                />
              </div>
              
              <div>
                <label className="block text-sm font-semibold text-gray-300 mb-2">
                  Message
                </label>
                <motion.textarea
                  whileFocus={{ scale: 1.02, borderColor: '#06b6d4' }}
                  value={formData.message}
                  onChange={(e) => setFormData({...formData, message: e.target.value})}
                  rows={6}
                  className="w-full px-4 py-3 bg-gray-900/50 border border-gray-600/50 rounded-xl text-white placeholder-gray-500 focus:outline-none focus:border-cyan-500 transition-all resize-none"
                  placeholder="Tell me about your project or just say hi!"
                  required
                />
              </div>
              
              <motion.button
                type="submit"
                disabled={isSubmitting}
                whileHover={!isSubmitting ? { 
                  scale: 1.05,
                  boxShadow: "0 0 30px rgba(6, 182, 212, 0.5)"
                } : {}}
                whileTap={!isSubmitting ? { scale: 0.95 } : {}}
                className="w-full py-4 bg-gradient-to-r from-cyan-600 to-purple-600 text-white rounded-xl font-bold text-lg hover:from-cyan-500 hover:to-purple-500 transition-all duration-300 flex items-center justify-center gap-3 disabled:opacity-50"
              >
                {isSubmitting ? (
                  <>
                    <motion.div
                      animate={{ rotate: 360 }}
                      transition={{ duration: 1, repeat: Infinity, ease: "linear" }}
                      className="w-6 h-6 border-2 border-white/30 border-t-white rounded-full"
                    />
                    Sending...
                  </>
                ) : (
                  <>
                    <Mail size={24} />
                    Send Message
                    <ArrowRight size={24} />
                  </>
                )}
              </motion.button>
            </form>
          </motion.div>
        </div>
      </motion.div>
    </section>
  );
};

// Enhanced Footer
const EnhancedFooter = () => {
  return (
    <footer className="py-16 px-8 lg:px-16 bg-gray-900/90 border-t border-gray-800 relative overflow-hidden">
      {/* Background animation */}
      <div className="absolute inset-0 opacity-20">
        {[...Array(20)].map((_, i) => (
          <motion.div
            key={i}
            className="absolute w-1import React, { useState, useEffect, useRef, useMemo } from 'react';
import { motion, AnimatePresence, useScroll, useTransform, useSpring, useInView, useMotionValue, useVelocity, wrap } from 'framer-motion';
import { ChevronDown, Github, ExternalLink, X, MessageCircle, Minimize2, Mail, Phone, MapPin, Calendar, Award, Code, Database, BarChart3, PenTool, Cloud, Bot, Sparkles, Zap, Star, Layers, Cpu, Target, Brain, Eye, Users, TrendingUp, Rocket, Heart, Coffee, Music, ArrowRight, ArrowUp, Globe, Linkedin, Twitter, Instagram, Play, Pause, Volume2 } from 'lucide-react';

// Enhanced Particle System with 3D effects
const EnhancedParticleSystem = () => {
  const [particles, setParticles] = useState([]);
  
  useEffect(() => {
    const newParticles = Array.from({ length: 80 }, (_, i) => ({
      id: i,
      x: Math.random() * window.innerWidth,
      y: Math.random() * window.innerHeight,
      size: Math.random() * 4 + 1,
      speedX: (Math.random() - 0.5) * 2,
      speedY: (Math.random() - 0.5) * 2,
      color: ['cyan', 'purple', 'pink', 'blue', 'green'][Math.floor(Math.random() * 5)],
      opacity: Math.random() * 0.8 + 0.2,
    }));
    setParticles(newParticles);
  }, []);

  return (
    <div className="fixed inset-0 overflow-hidden pointer-events-none z-0">
      {particles.map((particle) => (
        <motion.div
          key={particle.id}
          className={`absolute rounded-full bg-${particle.color}-500 blur-sm`}
          style={{
            width: particle.size,
            height: particle.size,
            opacity: particle.opacity,
          }}
          initial={{
            x: particle.x,
            y: particle.y,
          }}
          animate={{
            x: [particle.x, particle.x + particle.speedX * 200, particle.x],
            y: [particle.y, particle.y + particle.speedY * 200, particle.y],
            scale: [1, 1.5, 1],
            rotate: [0, 360],
          }}
          transition={{
            duration: Math.random() * 20 + 10,
            repeat: Infinity,
            ease: "linear"
          }}
        />
      ))}
      
      {/* Floating orbs */}
      {[...Array(12)].map((_, i) => (
        <motion.div
          key={`orb-${i}`}
          className={`absolute w-32 h-32 rounded-full blur-3xl opacity-20 ${
            i % 4 === 0 ? 'bg-cyan-500' : 
            i % 4 === 1 ? 'bg-purple-500' : 
            i % 4 === 2 ? 'bg-pink-500' : 'bg-blue-500'
          }`}
          initial={{
            x: Math.random() * window.innerWidth,
            y: Math.random() * window.innerHeight,
          }}
          animate={{
            x: Math.random() * window.innerWidth,
            y: Math.random() * window.innerHeight,
            scale: [0.8, 1.2, 0.8],
          }}
          transition={{
            duration: Math.random() * 30 + 20,
            repeat: Infinity,
            ease: "easeInOut"
          }}
        />
      ))}
    </div>
  );
};

// Enhanced TypeWriter with glitch effects
const EnhancedTypeWriter = ({ text, delay = 100 }) => {
  const [displayText, setDisplayText] = useState('');
  const [currentIndex, setCurrentIndex] = useState(0);
  const [isGlitching, setIsGlitching] = useState(false);

  useEffect(() => {
    if (currentIndex < text.length) {
      const timeout = setTimeout(() => {
        setDisplayText(prev => prev + text[currentIndex]);
        setCurrentIndex(prev => prev + 1);
        
        // Random glitch effect
        if (Math.random() < 0.1) {
          setIsGlitching(true);
          setTimeout(() => setIsGlitching(false), 100);
        }
      }, delay);
      return () => clearTimeout(timeout);
    }
  }, [currentIndex, text, delay]);

  return (
    <span className="font-mono relative">
      <motion.span
        className={isGlitching ? 'text-red-500 animate-pulse' : ''}
        animate={isGlitching ? { x: [-2, 2, -2, 2, 0] } : {}}
        transition={{ duration: 0.1 }}
      >
        {displayText}
      </motion.span>
      <motion.span
        animate={{ opacity: [1, 0] }}
        transition={{ duration: 0.8, repeat: Infinity }}
        className="text-cyan-400 ml-1"
      >
        ▌
      </motion.span>
    </span>
  );
};

// Music Visualizer Component
const MusicVisualizer = () => {
  const [isPlaying, setIsPlaying] = useState(false);
  const [bars, setBars] = useState([]);

  useEffect(() => {
    const newBars = Array.from({ length: 20 }, (_, i) => ({
      id: i,
      height: Math.random() * 100 + 20,
    }));
    setBars(newBars);

    if (isPlaying) {
      const interval = setInterval(() => {
        setBars(prev => prev.map(bar => ({
          ...bar,
          height: Math.random() * 100 + 20,
        })));
      }, 150);
      return () => clearInterval(interval);
    }
  }, [isPlaying]);

  return (
    <motion.div 
      className="fixed top-20 right-8 z-40 bg-gray-900/80 backdrop-blur-sm border border-cyan-500/30 rounded-xl p-4"
      initial={{ x: 100, opacity: 0 }}
      animate={{ x: 0, opacity: 1 }}
      transition={{ delay: 2 }}
    >
      <div className="flex items-center gap-3 mb-3">
        <motion.button
          onClick={() => setIsPlaying(!isPlaying)}
          whileHover={{ scale: 1.1 }}
          whileTap={{ scale: 0.9 }}
          className="w-8 h-8 bg-gradient-to-r from-cyan-500 to-purple-500 rounded-full flex items-center justify-center"
        >
          {isPlaying ? <Pause size={14} /> : <Play size={14} />}
        </motion.button>
        <Music className="text-cyan-400" size={16} />
        <Volume2 className="text-gray-400" size={14} />
      </div>
      
      <div className="flex items-end gap-1 h-16">
        {bars.map((bar) => (
          <motion.div
            key={bar.id}
            className="w-2 bg-gradient-to-t from-cyan-500 to-purple-500 rounded-t"
            animate={{ 
              height: isPlaying ? bar.height : 20,
              opacity: isPlaying ? [0.5, 1, 0.5] : 0.3,
            }}
            transition={{ 
              duration: 0.15,
              opacity: { duration: 0.5, repeat: Infinity }
            }}
          />
        ))}
      </div>
    </motion.div>
  );
};

// 3D Floating Robot with enhanced animations
const Enhanced3DRobot = () => {
  const [isOpen, setIsOpen] = useState(false);
  const [messages, setMessages] = useState([
    { type: 'bot', text: '🚀 Welcome to the future!', emoji: '🤖' },
    { type: 'bot', text: 'Kavya\'s AI-powered portfolio!', emoji: '⚡' }
  ]);
  const [isTyping, setIsTyping] = useState(false);

  const responses = [
    { text: "Kavya's AI/ML skills are incredible! 🧠", emoji: '🎯' },
    { text: "Check out those certifications! 🏆", emoji: '📜' },
    { text: "The projects showcase real innovation! 💡", emoji: '🚀' },
    { text: "Data analytics expertise at its finest! 📊", emoji: '💻' },
    { text: "Future AI engineer in the making! 🔮", emoji: '⭐' },
    { text: "Those skills are off the charts! 📈", emoji: '🎉' }
  ];

  const handleSendMessage = (text) => {
    setMessages(prev => [...prev, { type: 'user', text, emoji: '👤' }]);
    setIsTyping(true);
    
    setTimeout(() => {
      const response = responses[Math.floor(Math.random() * responses.length)];
      setMessages(prev => [...prev, { type: 'bot', text: response.text, emoji: response.emoji }]);
      setIsTyping(false);
    }, 1500);
  };

  return (
    <div className="fixed bottom-6 right-6 z-50">
      <AnimatePresence>
        {isOpen && (
          <motion.div
            initial={{ opacity: 0, scale: 0.8, rotateX: -90 }}
            animate={{ opacity: 1, scale: 1, rotateX: 0 }}
            exit={{ opacity: 0, scale: 0.8, rotateX: 90 }}
            transition={{ type: "spring", stiffness: 300, damping: 25 }}
            className="mb-4 w-96 bg-gradient-to-br from-gray-900 via-gray-800 to-gray-900 border border-cyan-500/50 rounded-2xl shadow-2xl overflow-hidden backdrop-blur-xl"
            style={{
              boxShadow: '0 0 50px rgba(6, 182, 212, 0.3), inset 0 0 50px rgba(147, 51, 234, 0.1)'
            }}
          >
            <motion.div 
              className="bg-gradient-to-r from-cyan-600 via-purple-600 to-pink-600 p-4 relative overflow-hidden"
              animate={{
                backgroundPosition: ['0% 50%', '100% 50%', '0% 50%'],
              }}
              transition={{
                duration: 3,
                repeat: Infinity,
                ease: "linear"
              }}
            >
              <div className="flex justify-between items-center relative z-10">
                <span className="text-white font-bold flex items-center gap-2">
                  <Bot className="animate-bounce" size={20} />
                  AI Assistant
                </span>
                <button
                  onClick={() => setIsOpen(false)}
                  className="text-white hover:text-gray-300 transition-colors"
                >
                  <X size={18} />
                </button>
              </div>
            </motion.div>
            
            <div className="h-72 overflow-y-auto p-4 space-y-3 bg-gradient-to-b from-transparent to-gray-900/50">
              {messages.map((msg, idx) => (
                <motion.div
                  key={idx}
                  initial={{ opacity: 0, y: 20, scale: 0.8 }}
                  animate={{ opacity: 1, y: 0, scale: 1 }}
                  transition={{ delay: idx * 0.1 }}
                  className={`flex ${msg.type === 'user' ? 'justify-end' : 'justify-start'}`}
                >
                  <div className={`max-w-xs p-3 rounded-2xl text-sm relative ${
                    msg.type === 'user'
                      ? 'bg-gradient-to-r from-cyan-600 to-blue-600 text-white'
                      : 'bg-gradient-to-r from-gray-800 to-gray-700 text-gray-100 border border-gray-600/50'
                  }`}>
                    <span className="mr-2">{msg.emoji}</span>
                    {msg.text}
                  </div>
                </motion.div>
              ))}
              
              {isTyping && (
                <motion.div
                  initial={{ opacity: 0 }}
                  animate={{ opacity: 1 }}
                  className="flex justify-start"
                >
                  <div className="bg-gradient-to-r from-gray-800 to-gray-700 text-gray-100 p-3 rounded-2xl">
                    <motion.div
                      className="flex space-x-1"
                      animate={{ opacity: [0.5, 1, 0.5] }}
                      transition={{ duration: 1.5, repeat: Infinity }}
                    >
                      <div className="w-2 h-2 bg-cyan-400 rounded-full animate-bounce" style={{ animationDelay: '0ms' }} />
                      <div className="w-2 h-2 bg-purple-400 rounded-full animate-bounce" style={{ animationDelay: '150ms' }} />
                      <div className="w-2 h-2 bg-pink-400 rounded-full animate-bounce" style={{ animationDelay: '300ms' }} />
                    </motion.div>
                  </div>
                </motion.div>
              )}
            </div>
            
            <div className="p-4 border-t border-gray-700/50 bg-gray-900/80">
              <div className="grid grid-cols-2 gap-2 mb-3">
                <motion.button
                  whileHover={{ scale: 1.05, backgroundColor: 'rgba(6, 182, 212, 0.2)' }}
                  whileTap={{ scale: 0.95 }}
                  onClick={() => handleSendMessage('Tell me about her skills')}
                  className="p-2 text-xs bg-gradient-to-r from-gray-800 to-gray-700 text-gray-300 rounded-lg hover:text-cyan-400 transition-all border border-gray-600/30"
                >
                  🎯 Skills
                </motion.button>
                <motion.button
                  whileHover={{ scale: 1.05, backgroundColor: 'rgba(147, 51, 234, 0.2)' }}
                  whileTap={{ scale: 0.95 }}
                  onClick={() => handleSendMessage('Show me projects')}
                  className="p-2 text-xs bg-gradient-to-r from-gray-800 to-gray-700 text-gray-300 rounded-lg hover:text-purple-400 transition-all border border-gray-600/30"
                >
                  🚀 Projects
                </motion.button>
              </div>
              <motion.button
                whileHover={{ scale: 1.02 }}
                whileTap={{ scale: 0.98 }}
                onClick={() => handleSendMessage('Amazing portfolio!')}
                className="w-full p-2 text-xs bg-gradient-to-r from-cyan-600 to-purple-600 text-white rounded-lg hover:from-cyan-500 hover:to-purple-500 transition-all"
              >
                ⭐ Compliment
              </motion.button>
            </div>
          </motion.div>
        )}
      </AnimatePresence>

      <motion.button
        onClick={() => setIsOpen(!isOpen)}
        whileHover={{ 
          scale: 1.1, 
          rotate: 360,
          boxShadow: "0 0 30px rgba(6, 182, 212, 0.6)"
        }}
        whileTap={{ scale: 0.9 }}
        animate={{
          y: [0, -15, 0],
          rotate: isOpen ? 0 : [0, 10, -10, 0],
        }}
        transition={{
          y: { duration: 2.5, repeat: Infinity, ease: "easeInOut" },
          rotate: { duration: 4, repeat: Infinity, ease: "easeInOut" }
        }}
        className="w-20 h-20 bg-gradient-to-r from-cyan-500 via-purple-500 to-pink-500 rounded-full flex items-center justify-center text-white shadow-2xl relative overflow-hidden group"
        style={{
          filter: 'drop-shadow(0 0 20px rgba(6, 182, 212, 0.5))'
        }}
      >
        <motion.div
          className="absolute inset-0 bg-gradient-to-r from-transparent via-white/20 to-transparent"
          animate={{
            x: [-100, 100],
            opacity: [0, 1, 0],
          }}
          transition={{
            duration: 2,
            repeat: Infinity,
            ease: "easeInOut"
          }}
        />
        <Bot size={28} className="relative z-10 group-hover:animate-pulse" />
      </motion.button>
    </div>
  );
};

// Floating Action Buttons
const FloatingActionButtons = () => {
  return (
    <motion.div 
      className="fixed left-6 top-1/2 transform -translate-y-1/2 z-40 space-y-4"
      initial={{ x: -100, opacity: 0 }}
      animate={{ x: 0, opacity: 1 }}
      transition={{ delay: 3, staggerChildren: 0.2 }}
    >
      {[
        { icon: Github, color: 'from-gray-600 to-gray-800', label: 'GitHub' },
        { icon: Linkedin, color: 'from-blue-600 to-blue-800', label: 'LinkedIn' },
        { icon: Mail, color: 'from-red-600 to-red-800', label: 'Email' },
        { icon: Coffee, color: 'from-yellow-600 to-orange-600', label: 'Buy Coffee' },
      ].map((item, index) => (
        <motion.div
          key={index}
          initial={{ x: -50, opacity: 0 }}
          animate={{ x: 0, opacity: 1 }}
          transition={{ delay: 3 + index * 0.2 }}
          className="group relative"
        >
          <motion.button
            whileHover={{ 
              scale: 1.2, 
              rotate: [0, -10, 10, 0],
              boxShadow: "0 0 25px rgba(6, 182, 212, 0.5)"
            }}
            whileTap={{ scale: 0.9 }}
            className={`w-14 h-14 bg-gradient-to-r ${item.color} rounded-full flex items-center justify-center text-white shadow-lg hover:shadow-2xl transition-all duration-300 relative overflow-hidden`}
          >
            <motion.div
              className="absolute inset-0 bg-gradient-to-r from-transparent via-white/10 to-transparent"
              animate={{
                x: [-50, 50],
                opacity: [0, 1, 0],
              }}
              transition={{
                duration: 2,
                repeat: Infinity,
                delay: index * 0.5,
                ease: "easeInOut"
              }}
            />
            <item.icon size={20} className="relative z-10" />
          </motion.button>
          
          <motion.div
            initial={{ opacity: 0, x: -20 }}
            whileHover={{ opacity: 1, x: 0 }}
            className="absolute left-16 top-1/2 transform -translate-y-1/2 bg-gray-900/90 backdrop-blur-sm text-white px-3 py-1 rounded-lg text-sm whitespace-nowrap pointer-events-none border border-cyan-500/30"
          >
            {item.label}
            <div className="absolute left-0 top-1/2 transform -translate-y-1/2 -translate-x-1 w-2 h-2 bg-gray-900 rotate-45 border-l border-b border-cyan-500/30" />
          </motion.div>
        </motion.div>
      ))}
    </motion.div>
  );
};

// Enhanced Hero Section
const EnhancedHero = () => {
  const { scrollY } = useScroll();
  const y1 = useTransform(scrollY, [0, 1000], [0, -200]);
  const y2 = useTransform(scrollY, [0, 1000], [0, -400]);
  const opacity = useTransform(scrollY, [0, 500], [1, 0]);
  
  return (
    <section className="min-h-screen flex items-center justify-between px-8 lg:px-16 relative overflow-hidden">
      {/* Animated background elements */}
      <motion.div
        style={{ y: y2, opacity }}
        className="absolute inset-0 bg-gradient-to-br from-cyan-500/5 via-purple-500/5 to-pink-500/5 rounded-full blur-3xl"
        animate={{
          scale: [1, 1.2, 1],
          rotate: [0, 180, 360],
        }}
        transition={{
          duration: 20,
          repeat: Infinity,
          ease: "linear"
        }}
      />

      <motion.div
        style={{ y: y1 }}
        initial={{ opacity: 0, x: -100 }}
        animate={{ opacity: 1, x: 0 }}
        transition={{ duration: 1.2, ease: "easeOut" }}
        className="flex-1 max-w-3xl relative z-10"
      >
        <motion.div
          initial={{ opacity: 0, scale: 0.5 }}
          animate={{ opacity: 1, scale: 1 }}
          transition={{ delay: 0.2, duration: 1, type: "spring" }}
          className="mb-6"
        >
          <span className="inline-block px-6 py-2 bg-gradient-to-r from-cyan-500/20 to-purple-500/20 border border-cyan-500/30 rounded-full text-cyan-400 text-sm font-semibold backdrop-blur-sm">
            ✨ Portfolio 2025
          </span>
        </motion.div>

        <motion.h1 
          className="text-7xl lg:text-9xl font-black mb-8 leading-none"
          initial={{ opacity: 0, y: 50 }}
          animate={{ opacity: 1, y: 0 }}
          transition={{ delay: 0.4, duration: 1.2, type: "spring" }}
        >
          <span className="block bg-gradient-to-r from-cyan-400 via-purple-400 to-pink-400 bg-clip-text text-transparent animate-gradient-x">
            Kavya
          </span>
          <motion.span 
            className="block bg-gradient-to-r from-pink-400 via-purple-400 to-cyan-400 bg-clip-text text-transparent"
            animate={{ 
              backgroundPosition: ['0% 50%', '100% 50%', '0% 50%'],
            }}
            transition={{
              duration: 5,
              repeat: Infinity,
              ease: "linear"
            }}
          >
            Rajput
          </motion.span>
        </motion.h1>
        
        <motion.div 
          className="text-3xl lg:text-4xl text-gray-300 mb-10 h-16 relative"
          initial={{ opacity: 0 }}
          animate={{ opacity: 1 }}
          transition={{ delay: 0.8 }}
        >
          <EnhancedTypeWriter text="AI Innovator | Data Wizard | Future Builder" delay={120} />
        </motion.div>

        <motion.p 
          className="text-2xl text-gray-400 mb-12 leading-relaxed max-w-2xl"
          initial={{ opacity: 0, y: 30 }}
          animate={{ opacity: 1, y: 0 }}
          transition={{ delay: 1.8, duration: 1 }}
        >
          Transforming data into intelligence, dreams into reality. 
          Building the future with <motion.span 
            className="text-transparent bg-gradient-to-r from-cyan-400 to-purple-400 bg-clip-text font-bold"
            animate={{ scale: [1, 1.05, 1] }}
            transition={{ duration: 2, repeat: Infinity }}
          >
            AI & Analytics
          </motion.span>
        </motion.p>

        <motion.div 
          className="flex gap-8 flex-wrap"
          initial={{ opacity: 0, y: 30 }}
          animate={{ opacity: 1, y: 0 }}
          transition={{ delay: 2.2, duration: 1 }}
        >
          <motion.button
            whileHover={{ 
              scale: 1.05, 
              boxShadow: "0 0 40px rgba(6, 182, 212, 0.6)",
              y: -5
            }}
            whileTap={{ scale: 0.95 }}
            className="px-10 py-5 bg-gradient-to-r from-cyan-600 via-blue-600 to-purple-600 text-white rounded-full font-bold text-lg hover:from-cyan-500 hover:to-purple-500 transition-all duration-300 flex items-center gap-3 relative overflow-hidden group"
          >
            <motion.div
              className="absolute inset-0 bg-gradient-to-r from-transparent via-white/10 to-transparent"
              animate={{
                x: [-100, 100],
                opacity: [0, 1, 0],
              }}
              transition={{
                duration: 2,
                repeat: Infinity,
                ease: "easeInOut"
              }}
            />
            <Rocket size={24} className="group-hover:animate-bounce" />
            <span className="relative z-10">Explore My Universe</span>
          </motion.button>
          
          <motion.button
            whileHover={{ 
              scale: 1.05,
              borderColor: '#06b6d4',
              y: -5
            }}
            whileTap={{ scale: 0.95 }}
            className="px-10 py-5 border-2 border-cyan-500/50 text-cyan-400 rounded-full font-bold text-lg hover:bg-cyan-500/10 transition-all duration-300 flex items-center gap-3 backdrop-blur-sm"
          >
            <MessageCircle size={24} />
            Let's Connect
          </motion.button>
        </motion.div>

        {/* Stats Counter */}
        <motion.div
          initial={{ opacity: 0, y: 30 }}
          animate={{ opacity: 1, y: 0 }}
          transition={{ delay: 2.8, duration: 1 }}
          className="mt-16 grid grid-cols-3 gap-8 max-w-lg"
        >
          {[
            { number: '15+', label: 'Certifications' },
            { number: '10+', label: 'Projects' },
            { number: '100%', label: 'Passion' },
          ].map((stat, index) => (
            <motion.div
              key={index}
              className="text-center"
              whileHover={{ scale: 1.1 }}
            >
              <motion.div
                className="text-3xl font-bold bg-gradient-to-r from-cyan-400 to-purple-400 bg-clip-text text-transparent"
                initial={{ scale: 0 }}
                animate={{ scale: 1 }}
                transition={{ delay: 3 + index * 0.2, type: "spring" }}
              >
                {stat.number}
              </motion.div>
              <div className="text-gray-500 text-sm mt-1">{stat.label}</div>
            </motion.div>
          ))}
        </motion.div>
      </motion.div>

      {/* Enhanced 3D Avatar */}
      <motion.div
        style={{ y: y1 }}
        initial={{ opacity: 0, scale: 0.8, rotateY: -30 }}
        animate={{ opacity: 1, scale: 1, rotateY: 0 }}
        transition={{ delay: 1.2, duration: 1.5, type: "spring" }}
        className="flex-1 flex justify-center items-center relative"
      >
        <div className="relative">
          {/* Orbiting rings */}
          {[...Array(3)].map((_, i) => (
            <motion.div
              key={i}
              animate={{ rotate: 360 }}
              transition={{
                duration: 20 - i * 5,
                repeat: Infinity,
                ease: "linear"
              }}
              className={`absolute inset-0 rounded-full border-2 ${
                i === 0 ? 'border-cyan-500/30 w-[500px] h-[500px]' :
                i === 1 ? 'border-purple-500/20 w-[400px] h-[400px] top-12 left-12' :
                'border-pink-500/20 w-[300px] h-[300px] top-24 left-24'
              }`}
              style={{
                borderStyle: i % 2 === 0 ? 'solid' : 'dashed'
              }}
            />
          ))}

          {/* Floating tech icons */}
          {[
            { icon: Brain, position: 'top-0 left-1/4', delay: 0 },
            { icon: Database, position: 'top-1/4 right-0', delay: 0.5 },
            { icon: BarChart3, position: 'bottom-1/4 left-0', delay: 1 },
            { icon: Cpu, position: 'bottom-0 right-1/4', delay: 1.5 },
          ].map(({ icon: Icon, position, delay }, index) => (
            <motion.div
              key={index}
              className={`absolute ${position} w-16 h-16 bg-gradient-to-r from-cyan-500/20 to-purple-500/20 rounded-full flex items-center justify-center backdrop-blur-sm border border-cyan-500/30`}
              animate={{
                y: [0, -20, 0],
                rotateY: [0, 180, 360],
                scale: [1, 1.1, 1],
              }}
              transition={{
                duration: 3,
                repeat: Infinity,
                delay: delay,
                ease: "easeInOut"
              }}
            >
              <Icon className="text-cyan-400" size={24} />
            </motion.div>
          ))}

          {/* Main avatar container */}
          <div className="relative w-[500px] h-[500px] bg-gradient-to-br from-cyan-400/10 via-purple-600/10 to-pink-400/10 rounded-full flex items-center justify-center backdrop-blur-sm border border-cyan-500/20">
            <motion.div
              animate={{
                y: [0, -30, 0],
                rotateY: [0, 10, -10, 0],
                scale: [1, 1.05, 1],
              }}
              transition={{
                duration: 6,
                repeat: Infinity,
                ease: "easeInOut"
              }}
              className="text-9xl relative z-10"
            >
              🚀
            </motion.div>
            
            {/* Glowing background effect */}
            <motion.div
              animate={{
                scale: [1, 1.3, 1],
                opacity: [0.2, 0.5, 0.2],
                rotate: [0, 180, 360],
              }}
              transition={{
                duration: 8,
                repeat: Infinity,
                ease: "easeInOut"
              }}
              className="absolute inset-0 rounded-full bg-gradient-to-r from-cyan-500/20 via-purple-500/20 to-pink-500/20 blur-3xl"
            />
          </div>

          {/* Particle trail */}
          {[...Array(8)].map((_, i) => (
            <motion.div
              key={`trail-${i}`}
              className="absolute w-4 h-4 bg-cyan-400/60 rounded-full"
              animate={{
                x: [
                  Math.cos(i * 45 * Math.PI / 180) * 200,
                  Math.cos(i * 45 * Math.PI / 180) * 250,
                  Math.cos(i * 45 * Math.PI / 180) * 200,
                ],
                y: [
                  Math.sin(i * 45 * Math.PI / 180) * 200,
                  Math.sin(i * 45 * Math.PI / 180) * 250,
                  Math.sin(i * 45 * Math.PI / 180) * 200,
                ],
                opacity: [0, 1, 0],
                scale: [0, 1, 0],
              }}
              transition={{
                duration: 2,
                repeat: Infinity,
                delay: i * 0.2,
                ease: "easeInOut"
              }}
              style={{
                left: '50%',
                top: '50%',
                transform: 'translate(-50%, -50%)',
              }}
            />
          ))}
        </div>
      </motion.div>
    </section>
  );
};

// Enhanced About Section
const EnhancedAbout = () => {
  const ref = useRef(null);
  const isInView = useInView(ref, { once: true });
  const { scrollYProgress } = useScroll({
    target: ref,
    offset: ["start end", "end start"]
  });
  
  const y = useTransform(scrollYProgress, [0, 1], [100, -100]);

  return (
    <section ref={ref} className="py-32 px-8 lg:px-16 relative overflow-hidden" id="about">
      {/* Animated background */}
      <motion.div
        style={{ y }}
        className="absolute inset-0 bg-gradient-to-r from-cyan-500/5 via-transparent to-purple-500/5 rounded-full blur-3xl"
      />

      <motion.div
        initial={{ opacity: 0, y: 100 }}
        animate={isInView ? { opacity: 1, y: 0 } : {}}
        transition={{ duration: 1, ease: "easeOut" }}
        className="max-w-6xl mx-auto"
      >
        <motion.h2 
          className="text-6xl lg:text-7xl font-black text-center mb-20 relative"
          initial={{ opacity: 0, scale: 0.5 }}
          animate={isInView ? { opacity: 1, scale: 1 } : {}}
          transition={{ delay: 0.2, duration: 1, type: "spring" }}
        >
          <span className="bg-gradient-to-r from-cyan-400 via-purple-400 to-pink-400 bg-clip-text text-transparent">
            About Me
          </span>
          <motion.div
            className="absolute -inset-4 bg-gradient-to-r from-cyan-500/20 to-purple-500/20 rounded-2xl blur-xl"
            animate={{
              scale: [1, 1.1, 1],
              opacity: [0.3, 0.6, 0.3],
            }}
            transition={{
              duration: 3,
              repeat: Infinity,
              ease: "easeInOut"
            }}
          />
        </motion.h2>

        <div className="grid lg:grid-cols-2 gap-16 items-center">
          {/* Text Content */}
          <motion.div
            initial={{ opacity: 0, x: -100 }}
            animate={isInView ? { opacity: 1, x: 0 } : {}}
            transition={{ delay: 0.4, duration: 1 }}
            className="space-y-8"
          >
            <motion.p 
              className="text-2xl text-gray-300 leading-relaxed"
              initial={{ opacity: 0, y: 30 }}
              animate={isInView ? { opacity: 1, y: 0 } : {}}
              transition={{ delay: 0.6, duration: 1 }}
            >
              I'm a passionate <motion.span 
                className="text-transparent bg-gradient-to-r from-cyan-400 to-purple-400 bg-clip-text font-bold"
                animate={{ scale: [1, 1.05, 1] }}
                transition={{ duration: 2, repeat: Infinity }}
              >B.Tech student</motion.span> with an insatiable curiosity for 
              Artificial Intelligence, Machine Learning, and Data Analytics.
            </motion.p>

            <motion.p 
              className="text-xl text-gray-400 leading-relaxed"
              initial={{ opacity: 0, y: 30 }}
              animate={isInView ? { opacity: 1, y: 0 } : {}}
              transition={{ delay: 0.8, duration: 1 }}
            >
              My mission? To bridge the gap between complex data and meaningful insights, 
              creating intelligent solutions that transform how we understand and interact with technology.
            </motion.p>

            {/* Achievement badges */}
            <motion.div 
              className="grid grid-cols-2 gap-4"
              initial={{ opacity: 0, y: 30 }}
              animate={isInView ? { opacity: 1, y: 0 } : {}}
              transition={{ delay: 1, duration: 1 }}
            >
              {[
                { icon: Target, text: "Problem Solver", color: "from-red-500 to-pink-500" },
                { icon: Brain, text: "AI Enthusiast", color: "from-blue-500 to-cyan-500" },
                { icon: TrendingUp, text: "Data Driven", color: "from-green-500 to-emerald-500" },
                { icon: Heart, text: "Innovation Lover", color: "from-purple-500 to-pink-500" },
              ].map((badge, index) => (
                <motion.div
                  key={index}
                  whileHover={{ scale: 1.05, rotateY: 10 }}
                  className={`bg-gradient-to-r ${badge.color} p-4 rounded-2xl text-white font-semibold flex items-center gap-3 backdrop-blur-sm border border-white/20`}
                  initial={{ opacity: 0, scale: 0 }}
                  animate={isInView ? { opacity: 1, scale: 1 } : {}}
                  transition={{ delay: 1.2 + index * 0.1, type: "spring" }}
                >
                  <badge.icon size={24} />
                  <span>{badge.text}</span>
                </motion.div>
              ))}
            </motion.div>
          </motion.div>

          {/* Interactive Info Cards */}
          <motion.div
            initial={{ opacity: 0, x: 100 }}
            animate={isInView ? { opacity: 1, x: 0 } : {}}
            transition={{ delay: 0.4, duration: 1 }}
            className="space-y-6"
          >
            {[
              { 
                icon: Calendar, 
                label: "Current Status", 
                value: "B.Tech Student", 
                detail: "Pursuing Excellence",
                color: "from-cyan-500 to-blue-500"
              },
              { 
                icon: MapPin, 
                label: "Location", 
                value: "India", 
                detail: "Building Global Solutions",
                color: "from-purple-500 to-pink-500"
              },
              { 
                icon: Zap, 
                label: "Specialization", 
                value: "AI/ML", 
                detail: "Future Technology",
                color: "from-yellow-500 to-orange-500"
              },
              { 
                icon: BarChart3, 
                label: "Expertise", 
                value: "Data Analytics", 
                detail: "Insights & Intelligence",
                color: "from-green-500 to-emerald-500"
              },
            ].map((item, index) => (
              <motion.div
                key={index}
                whileHover={{ 
                  scale: 1.05, 
                  rotateY: 5,
                  boxShadow: "0 0 30px rgba(6, 182, 212, 0.3)"
                }}
                className="bg-gray-800/80 backdrop-blur-sm border border-gray-700/50 rounded-2xl p-6 hover:border-cyan-500/50 transition-all duration-300 group relative overflow-hidden"
                initial={{ opacity: 0, y: 50 }}
                animate={isInView ? { opacity: 1, y: 0 } : {}}
                transition={{ delay: 0.8 + index * 0.1, duration: 0.8 }}
              >
                <motion.div
                  className={`absolute inset-0 bg-gradient-to-r ${item.color} opacity-0 group-hover:opacity-10 transition-opacity duration-300`}
                  whileHover={{ scale: 1.1 }}
                />
                
                <div className="flex items-start gap-4 relative z-10">
                  <motion.div
                    className={`w-14 h-14 rounded-2xl bg-gradient-to-r ${item.color} flex items-center justify-center group-hover:scale-110 transition-transform duration-300`}
                    whileHover={{ rotate: 360 }}
                    transition={{ duration: 0.6 }}
                  >
                    <item.icon size={24} className="text-white" />
                  </motion.div>
                  
                  <div className="flex-1">
                    <div className="text-sm text-gray-400 mb-1">{item.label}</div>
                    <div className="text-2xl font-bold text-white mb-1 group-hover:text-cyan-400 transition-colors">
                      {item.value}
                    </div>
                    <div className="text-sm text-gray-500">{item.detail}</div>
                  </div>
                </div>
              </motion.div>
            ))}
          </motion.div>
        </div>

        {/* Call to action */}
        <motion.div
          className="text-center mt-20"
          initial={{ opacity: 0, y: 50 }}
          animate={isInView ? { opacity: 1, y: 0 } : {}}
          transition={{ delay: 1.4, duration: 1 }}
        >
          <motion.button
            whileHover={{ 
              scale: 1.05,
              boxShadow: "0 0 40px rgba(6, 182, 212, 0.5)"
            }}
            whileTap={{ scale: 0.95 }}
            className="px-12 py-4 bg-gradient-to-r from-cyan-600 to-purple-600 text-white rounded-full font-bold text-lg hover:from-cyan-500 hover:to-purple-500 transition-all duration-300 flex items-center gap-3 mx-auto"
          >
            <Eye size={24} />
            See My Journey
            <ArrowRight size={24} />
          </motion.button>
        </motion.div>
      </motion.div>
    </section>
  );
};

// Ultra-Enhanced Skills Section
const UltraSkills = () => {
  const ref = useRef(null);
  const isInView = useInView(ref, { once: true });

  const skills = [
    { 
      name: 'AI/ML', 
      icon: Brain, 
      color: 'from-cyan-500 to-blue-500', 
      level: 85,
      description: 'Neural Networks & Deep Learning',
      projects: 8
    },
    { 
      name: 'Data Analytics', 
      icon: BarChart3, 
      color: 'from-purple-500 to-pink-500', 
      level: 90,
      description: 'Statistical Analysis & Visualization',
      projects: 12
    },
    { 
      name: 'Python', 
      icon: Code, 
      color: 'from-yellow-500 to-orange-500', 
      level: 88,
      description: 'Advanced Programming & Libraries',
      projects: 15
    },
    { 
      name: 'SQL', 
      icon: Database, 
      color: 'from-blue-500 to-indigo-500', 
      level: 82,
      description: 'Complex Queries & Optimization',
      projects: 10
    },
    { 
      name: 'Tableau', 
      icon: BarChart3, 
      color: 'from-red-500 to-pink-500', 
      level: 78,
      description: 'Interactive Dashboards',
      projects: 6
    },
    { 
      name: 'Azure', 
      icon: Cloud, 
      color: 'from-cyan-500 to-blue-600', 
      level: 75,
      description: 'Cloud Computing & Services',
      projects: 4
    },
    { 
      name: 'JavaScript', 
      icon: Code, 
      color: 'from-green-500 to-emerald-500', 
      level: 80,
      description: 'Modern Web Development',
      projects: 9
    },
    { 
      name: 'AutoCAD', 
      icon: PenTool, 
      color: 'from-gray-500 to-slate-500', 
      level: 70,
      description: 'Technical Design & Modeling',
      projects: 5
    },
  ];

  return (
    <section ref={ref} className="py-32 px-8 lg:px-16 bg-gray-900/50 relative overflow-hidden" id="skills">
      {/* Animated mesh background */}
      <div className="absolute inset-0 opacity-20">
        <div className="absolute inset-0 bg-gradient-to-r from-cyan-500/10 via-purple-500/10 to-pink-500/10" />
        <motion.div
          animate={{
            backgroundPosition: ['0% 0%', '100% 100%'],
          }}
          transition={{
            duration: 20,
            repeat: Infinity,
            ease: "linear"
          }}
          className="absolute inset-0 opacity-30"
          style={{
            backgroundImage: `
              radial-gradient(circle at 20% 20%, rgba(6, 182, 212, 0.3) 0%, transparent 50%),
              radial-gradient(circle at 80% 20%, rgba(147, 51, 234, 0.3) 0%, transparent 50%),
              radial-gradient(circle at 40% 80%, rgba(236, 72, 153, 0.3) 0%, transparent 50%)
            `
          }}
        />
      </div>

      <motion.div
        initial={{ opacity: 0 }}
        animate={isInView ? { opacity: 1 } : {}}
        transition={{ duration: 1 }}
        className="max-w-7xl mx-auto relative z-10"
      >
        <motion.h2 
          className="text-6xl lg:text-7xl font-black text-center mb-8 relative"
          initial={{ opacity: 0, y: 100 }}
          animate={isInView ? { opacity: 1, y: 0 } : {}}
          transition={{ duration: 1, type: "spring" }}
        >
          <span className="bg-gradient-to-r from-cyan-400 via-purple-400 to-pink-400 bg-clip-text text-transparent">
            Skills & Expertise
          </span>
        </motion.h2>

        <motion.p
          className="text-2xl text-gray-400 text-center mb-20 max-w-3xl mx-auto"
          initial={{ opacity: 0, y: 50 }}
          animate={isInView ? { opacity: 1, y: 0 } : {}}
          transition={{ delay: 0.3, duration: 1 }}
        >
          Mastering the tools that shape tomorrow's technology landscape
        </motion.p>

        <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
          {skills.map((skill, index) => (
            <motion.div
              key={skill.name}
              initial={{ opacity: 0, y: 100, rotateX: -90 }}
              animate={isInView ? { opacity: 1, y: 0, rotateX: 0 } : {}}
              whileHover={{ 
                scale: 1.05, 
                rotateY: 10,
                boxShadow: "0 0 50px rgba(6, 182, 212, 0.4)"
              }}
              transition={{ 
                delay: index * 0.1, 
                duration: 0.8,
                type: "spring",
                stiffness: 100
              }}
              className="group bg-gray-800/80 backdrop-blur-sm border border-gray-700/50 rounded-3xl p-8 text-center hover:border-cyan-500/50 transition-all duration-500 relative overflow-hidden"
            >
              {/* Animated background gradient */}
              <motion.div
                className={`absolute inset-0 bg-gradient-to-br ${skill.color} opacity-0 group-hover:opacity-10 transition-opacity duration-500`}
                whileHover={{ scale: 1.2, rotate: 180 }}
                transition={{ duration: 0.8 }}
              />

              {/* Skill icon */}
              <motion.div
                className={`w-20 h-20 mx-auto mb-6 rounded-3xl bg-gradient-to-r ${skill.color} flex items-center justify-center relative overflow-hidden`}
                whileHover={{ 
                  scale: 1.2, 
                  rotate: 360,
                }}
                transition={{ 
                  duration: 0.6,
                  type: "spring",
                  stiffness: 200
                }}
              >
                <motion.div
                  className="absolute inset-0 bg-gradient-to-r from-transparent via-white/20 to-transparent"
                  animate={{
                    x: [-50, 50],
                    opacity: [0, 1, 0],
                  }}
                  transition={{
                    duration: 2,
                    repeat: Infinity,
                    delay: index * 0.2,
                    ease: "easeInOut"
                  }}
                />
                <skill.icon size={28} className="text-white relative z-10" />
              </motion.div>

              <h3 className="text-2xl font-bold text-white mb-3 group-hover:text-cyan-400 transition-colors">
                {skill.name}
              </h3>

              <p className="text-gray-400 mb-6 text-sm leading-relaxed">
                {skill.description}
              </p>

              {/* Skill level progress */}
              <div className="mb-4">
                <div className="flex justify-between mb-2">
                  <span className="text-sm text-gray-400">Proficiency</span>
                  <span className="text-sm font-bold text-cyan-400">{skill.level}%</span>
                </div>
                <div className="w-full bg-gray-700/50 rounded-full h-3 overflow-hidden">
                  <motion.div
                    className={`h-3 bg-gradient-to-r ${skill.color} rounded-full relative overflow-hidden`}
                    initial={{ width: 0 }}
                    animate={isInView ? { width: `${skill.level}%` } : {}}
                    transition={{ 
                      delay: index * 0.1 + 0.5, 
                      duration: 1.5,
                      ease: "easeOut"
                    }}
                  >
                    <motion.div
                      className="absolute inset-0 bg-gradient-to-r from-transparent via-white/30 to-transparent"
                      animate={{
                        x: ['-100%', '100%'],
                        opacity: [0, 1, 0],
                      }}
                      transition={{
                        duration: 2,
                        repeat: Infinity,
                        delay: index * 0.3,
                        ease: "easeInOut"
                      }}
                    />
                  </motion.div>
                </div>
              </div>

              {/* Projects count */}
              <motion.div
                className="flex items-center justify-center gap-2 text-gray-500"
                whileHover={{ scale: 1.1 }}
              >
                <Layers size={16} />
                <span className="text-sm">{skill.projects} Projects</span>
              </motion.div>

              {/* Hover effect particles */}
              <div className="absolute inset-0 pointer-events-none">
                {[...Array(6)].map((_, i) => (
                  <motion.div
                    key={i}
                    className={`absolute w-1 h-1 bg-cyan-400 rounded-full opacity-0 group-hover:opacity-100`}
                    style={{
                      left: `${20 + i * 12}%`,
                      top: `${20 + (i % 2) * 60}%`,
                    }}
                    animate={{
                      y: [0, -20, 0],
                      opacity: [0, 1, 0],
                    }}
                    transition={{
                      duration: 2,
                      repeat: Infinity,
                      delay: i * 0.2,
                      ease: "easeInOut"
                    }}
                  />
                ))}
              </div>
            </motion.div>
          ))}
        </div>

        {/* Skills summary */}
        <motion.div
          className="mt-20 text-center"
          initial={{ opacity: 0, y: 50 }}
          animate={isInView ? { opacity: 1, y: 0 } : {}}
          transition={{ delay: 1, duration: 1 }}
        >
          <motion.div
            className="inline-flex items-center gap-4 bg-gray-800/80 backdrop-blur-sm border border-cyan-500/30 rounded-full px-8 py-4"
            whileHover={{ 
              scale: 1.05,
              boxShadow: "0 0 30px rgba(6, 182, 212, 0.3)"
            }}
          >
            <Star className="text-cyan-400" size={24} />
            <span className="text-xl font-semibold text-white">
              Average Proficiency: <span className="text-cyan-400">81%</span>
            </span>
            <Star className="text-cyan-400" size={24} />
          </motion.div>
        </motion.div>
      </motion.div>
    </section>
  );
};

// Rest of the components will continue in the next part...

// Navigation with glassmorphism
const GlassNavigation = () => {
  const [isOpen, setIsOpen] = useState(false);
  const [activeSection, setActiveSection] = useState('home');
  const { scrollY } = useScroll();
  const backgroundColor = useTransform(
    scrollY,
    [0, 100],
    ['rgba(17, 24, 39, 0)', 'rgba(17, 24, 39, 0.8)']
  );

  const navItems = [
    { name: 'Home', href: '#home', icon: '🏠' },
    { name: 'About', href: '#about', icon: '👋' },
    { name: 'Skills', href: '#skills', icon: '⚡' },
    { name: 'Certificates', href: '#certificates', icon: '🏆' },
    { name: 'Projects', href: '#projects', icon: '🚀' },
    { name: 'Contact', href: '#contact', icon: '📧' }
  ];

  useEffect(() => {
    const handleScroll = () => {
      const sections = navItems.map(item => item.href.slice(1));
      const currentSection = sections.find(section => {
        const element = document.getElementById(section);
        if (element) {
          const rect = element.getBoundingClientRect();
          return rect.top <= 100 && rect.bottom >= 100;
        }
        return false;
      });
      if (currentSection) {
        setActiveSection(currentSection);
      }
    };

    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  }, []);

  return (
    <motion.nav
      style={{ backgroundColor }}
      className="fixed top-0 left-0 right-0 z-50 backdrop-blur-xl border-b border-white/10"
      initial={{ y: -100 }}
      animate={{ y: 0 }}
      transition={{ duration: 0.8, type: "spring" }}
    >
      <div className="max-w-7xl mx-auto px-8">
        <div className="flex justify-between items-center h-20">
          <motion.div
            whileHover={{ scale: 1.1, rotate: 5 }}
            className="text-3xl font-black bg-gradient-to-r from-cyan-400 via-purple-400 to-pink-400 bg-clip-text text-transparent cursor-pointer relative"
          >
            KR
            <motion.div
              className="absolute -inset-2 bg-gradient-to-r from-cyan-500/20 to-purple-500/20 rounded-full blur-xl"
              animate={{
                scale: [1, 1.2, 1],
                opacity: [0.3, 0.6, 0.3],
              }}
              transition={{
                duration: 2,
                repeat: Infinity,
                ease: "easeInOut"
              }}
            />
          </motion.div>
          
          <div className="hidden md:flex items-center space-x-2">
            {navItems.map((item) => (
              <motion.a
                key={item.name}
                href={item.href}
                whileHover={{ scale: 1.05 }}
                whileTap={{ scale: 0.95 }}
                className={`px-6 py-3 rounded-full font-semibold transition-all duration-300 flex items-center gap-2 ${
                  activeSection === item.href.slice(1)
                    ? 'bg-gradient-to-r from-cyan-600/20 to-purple-600/20 text-cyan-400 border border-cyan-500/30'
                    : 'text-gray-300 hover:text-cyan-400 hover:bg-white/5'
                }`}
              >
                <span>{item.icon}</span>
                <span>{item.name}</span>
              </motion.a>
            ))}
          </div>
          
          <motion.button
            onClick={() => setIsOpen(!isOpen)}
            whileHover={{ scale: 1.1 }}
            whileTap={{ scale: 0.9 }}
            className="md:hidden w-12 h-12 rounded-full bg-gradient-to-r from-cyan-500/20 to-purple-500/20 border border-cyan-500/30 backdrop-blur-sm flex items-center justify-center"
          >
            <motion.div
              animate={{ rotate: isOpen ? 45 : 0 }}
              transition={{ duration: 0.3 }}
            >
              <div className={`w-6 h-0.5 bg-white transition-all ${isOpen ? 'rotate-45 translate-y-0.5' : ''}`} />
              <div className={`w-6 h-0.5 bg-white mt-1 transition-all ${isOpen ? '-rotate-45 -translate-y-0.5' : ''}`} />
            </motion.div>
          </motion.button>
        </div>
        
        <AnimatePresence>
          {isOpen && (
            <motion.div
              initial={{ opacity: 0, height: 0 }}
              animate={{ opacity: 1, height: 'auto' }}
              exit={{ opacity: 0, height: 0 }}
              className="md:hidden py-6 border-t border-white/10 backdrop-blur-sm"
            >
              {navItems.map((item, index) => (
                <motion.a
                  key={item.name}
                  href={item.href}
                  initial={{ opacity: 0, x: -50 }}
                  animate={{ opacity: 1, x: 0 }}
                  transition={{ delay: index * 0.1 }}
                  className="flex items-center gap-3 py-3 px-4 text-gray-300 hover:text-cyan-400 transition-colors rounded-lg hover:bg-white/5"
                  onClick={() => setIsOpen(false)}
                >
                  <span className="text-xl">{item.icon}</span>
                  <span className="font-semibold">{item.name}</span>
                </motion.a>
              ))}
            </motion.div>
          )}
        </AnimatePresence>
      </div>
    </motion.nav>
  );
};

// Ultra-Enhanced Certificates Section
const UltraCertificates = () => {
  const ref = useRef(null);
  const isInView = useInView(ref, { once: true });

  const certificates = [
    {
      title: 'Data Analytics Job Simulation',
      issuer: 'Deloitte',
      date: 'May 31st, 2025',
      skills: ['Data analysis', 'Forensic technology', 'Business Intelligence'],
      level: 'Professional',
      credentialId: 'DEL-2025-DA-001',
      icon: '📊',
      color: 'from-blue-500 to-cyan-500'
    },
    {
      title: 'Technology Job Simulation',
      issuer: 'Deloitte',
      date: 'May 30th, 2025',
      skills: ['Coding', 'Development', 'System Design'],
      level: 'Professional',
      credentialId: 'DEL-2025-TS-002',
      icon: '💻',
      color: 'from-purple-500 to-blue-500'
    },
    {
      title: 'Problem Solving (Intermediate)',
      issuer: 'HackerRank',
      date: 'Dec 05, 2024',
      skills: ['Algorithms', 'Data Structures', 'Logic Building'],
      level: 'Intermediate',
      credentialId: 'HR-PS-INT-2024',
      icon: '🧩',
      color: 'from-green-500 to-teal-500'
    },
    {
      title: 'SQL (Basic)',
      issuer: 'HackerRank',
      date: 'Aug 02, 2025',
      skills: ['Database Management', 'Query Optimization', 'Data Modeling'],
      level: 'Basic',
      credentialId: 'HR-SQL-BAS-2025',
      icon: '🗃️',
      color: 'from-yellow-500 to-orange-500'
    },
    {
      title: 'Python (Basic)',
      issuer: 'HackerRank',
      date: 'May 03, 2025',
      skills: ['Programming', 'Data Structures', 'OOP Concepts'],
      level: 'Basic',
      credentialId: 'HR-PY-BAS-2025',
      icon: '🐍',
      color: 'from-red-500 to-pink-500'
    },
    {
      title: 'Azure Fundamentals',
      issuer: 'Microsoft',
      date: 'Jan 18, 2025',
      skills: ['Cloud Computing', 'Azure Services', 'Cloud Architecture'],
      level: 'Fundamentals',
      credentialId: 'MS-AZ-900-2025',
      icon: '☁️',
      color: 'from-cyan-500 to-blue-600'
    },
    {
      title: 'JavaScript',
      issuer: 'Infosys Springboard',
      date: 'Nov 24, 2024',
      skills: ['Web Development', 'Programming', 'DOM Manipulation'],
      level: 'Intermediate',
      credentialId: 'INF-JS-2024',
      icon: '⚡',
      color: 'from-yellow-400 to-yellow-600'
    },
    {
      title: 'HTML5 - The Language',
      issuer: 'Infosys Springboard',
      date: 'Nov 20, 2024',
      skills: ['Web Development', 'Frontend', 'Semantic HTML'],
      level: 'Basic',
      credentialId: 'INF-HTML5-2024',
      icon: '🏗️',
      color: 'from-orange-500 to-red-500'
    },
    {
      title: 'CSS3',
      issuer: 'Infosys Springboard',
      date: 'Nov 24, 2024',
      skills: ['Styling', 'Web Design', 'Responsive Design'],
      level: 'Basic',
      credentialId: 'INF-CSS3-2024',
      icon: '🎨',
      color: 'from-purple-500 to-indigo-500'
    }
  ];

  return (
    <section ref={ref} className="py-32 px-8 lg:px-16 relative overflow-hidden" id="certificates">
      {/* Animated background */}
      <div className="absolute inset-0">
        <motion.div
          animate={{
            rotate: [0, 360],
            scale: [1, 1.2, 1],
          }}
          transition={{
            duration: 30,
            repeat: Infinity,
            ease: "linear"
          }}
          className="absolute -top-1/2 -right-1/2 w-full h-full bg-gradient-to-r from-cyan-500/5 via-purple-500/5 to-pink-500/5 rounded-full blur-3xl"
        />
      </div>

      <motion.div
        initial={{ opacity: 0 }}
        animate={isInView ? { opacity: 1 } : {}}
        transition={{ duration: 1 }}
        className="max-w-7xl mx-auto relative z-10"
      >
        <motion.div
          className="text-center mb-20"
          initial={{ opacity: 0, y: 100 }}
          animate={isInView ? { opacity: 1, y: 0 } : {}}
          transition={{ duration: 1, type: "spring" }}
        >
          <motion.h2 
            className="text-6xl lg:text-7xl font-black mb-6 relative inline-block"
          >
            <span className="bg-gradient-to-r from-cyan-400 via-purple-400 to-pink-400 bg-clip-text text-transparent">
              Certificates & Achievements
            </span>
            <motion.div
              className="absolute -inset-4 bg-gradient-to-r from-cyan-500/20 to-purple-500/20 rounded-2xl blur-xl"
              animate={{
                scale: [1, 1.1, 1],
                opacity: [0.3, 0.6, 0.3],
              }}
              transition={{
                duration: 3,
                repeat: Infinity,
                ease: "easeInOut"
              }}
            />
          </motion.h2>
          
          <motion.p
            className="text-2xl text-gray-400 max-w-3xl mx-auto"
            initial={{ opacity: 0, y: 30 }}
            animate={isInView ? { opacity: 1, y: 0 } : {}}
            transition={{ delay: 0.3, duration: 1 }}
          >
            Professional certifications validating expertise and commitment to continuous learning
          </motion.p>

          <motion.div
            className="flex justify-center gap-8 mt-8"
            initial={{ opacity: 0, scale: 0 }}
            animate={isInView ? { opacity: 1, scale: 1 } : {}}
            transition={{ delay: 0.5, duration: 1, type: "spring" }}
          >
            <div className="text-center">
              <div className="text-4xl font-bold text-cyan-400">15+</div>
              <div className="text-gray-500">Certifications</div>
            </div>
            <div className="text-center">
              <div className="text-4xl font-bold text-purple-400">5+</div>
              <div className="text-gray-500">Platforms</div>
            </div>
            <div className="text-center">
              <div className="text-4xl font-bold text-pink-400">100%</div>
              <div className="text-gray-500">Verified</div>
            </div>
          </motion.div>
        </motion.div>

        <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          {certificates.map((cert, index) => (
            <motion.div
              key={index}
              initial={{ opacity: 0, y: 100, rotateX: -45 }}
              animate={isInView ? { opacity: 1, y: 0, rotateX: 0 } : {}}
              whileHover={{ 
                scale: 1.05, 
                rotateY: 5,
                boxShadow: "0 0 50px rgba(6, 182, 212, 0.4)",
                z: 10
              }}
              transition={{ 
                delay: index * 0.1, 
                duration: 0.8,
                type: "spring"
              }}
              className="group bg-gray-800/80 backdrop-blur-sm border border-gray-700/50 rounded-3xl overflow-hidden hover:border-cyan-500/50 transition-all duration-500 relative"
            >
              {/* Animated background */}
              <motion.div
                className={`absolute inset-0 bg-gradient-to-br ${cert.color} opacity-0 group-hover:opacity-10 transition-opacity duration-500`}
                whileHover={{ scale: 1.1, rotate: 5 }}
              />

              {/* Header with icon and level */}
              <div className="p-6 pb-4 relative z-10">
                <div className="flex items-center justify-between mb-4">
                  <motion.div
                    className={`w-16 h-16 rounded-2xl bg-gradient-to-r ${cert.color} flex items-center justify-center text-2xl relative overflow-hidden`}
                    whileHover={{ rotate: 360, scale: 1.1 }}
                    transition={{ duration: 0.6 }}
                  >
                    <motion.div
                      className="absolute inset-0 bg-gradient-to-r from-transparent via-white/20 to-transparent"
                      animate={{
                        x: [-50, 50],
                        opacity: [0, 1, 0],
                      }}
                      transition={{
                        duration: 2,
                        repeat: Infinity,
                        delay: index * 0.2,
                        ease: "easeInOut"
                      }}
                    />
                    <span className="relative z-10">{cert.icon}</span>
                  </motion.div>
                  
                  <motion.div
                    className={`px-3 py-1 rounded-full text-xs font-semibold bg-gradient-to-r ${cert.color} text-white`}
                    whileHover={{ scale: 1.1 }}
                  >
                    {cert.level}
                  </motion.div>
                </div>

                <h3 className="text-xl font-bold text-white mb-2 group-hover:text-cyan-400 transition-colors line-clamp-2">
                  {cert.title}
                </h3>
                
                <div className="flex items-center gap-2 mb-4">
                  <motion.div
                    className={`w-8 h-8 rounded-full bg-gradient-to-r ${cert.color} flex items-center justify-center`}
                    whileHover={{ rotate: 180 }}
                    transition={{ duration: 0.5 }}
                  >
                    <Award size={16} className="text-white" />
                  </motion.div>
                  <div>
                    <p className="text-cyan-400 font-semibold text-sm">{cert.issuer}</p>
                    <p className="text-gray-500 text-xs">{cert.date}</p>
                  </div>
                </div>

                <div className="mb-4">
                  <p className="text-xs text-gray-500 mb-2">Skills Validated:</p>
                  <div className="flex flex-wrap gap-2">
                    {cert.skills.map((skill, idx) => (
                      <motion.span
                        key={idx}
                        whileHover={{ scale: 1.05 }}
                        className="px-2 py-1 bg-gray-700/50 text-gray-300 text-xs rounded-full border border-gray-600/50 hover:border-cyan-500/50 transition-colors"
                      >
                        {skill}
                      </motion.span>
                    ))}
                  </div>
                </div>

                <div className="border-t border-gray-700/50 pt-4">
                  <p className="text-xs text-gray-500 mb-2">Credential ID:</p>
                  <p className="text-xs text-cyan-400 font-mono">{cert.credentialId}</p>
                </div>
              </div>

              {/* Hover effect particles */}
              <div className="absolute inset-0 pointer-events-none overflow-hidden">
                {[...Array(8)].map((_, i) => (
                  <motion.div
                    key={i}
                    className="absolute w-2 h-2 bg-cyan-400/60 rounded-full opacity-0 group-hover:opacity-100"
                    style={{
                      left: `${Math.random() * 100}%`,
                      top: `${Math.random() * 100}%`,
                    }}
                    animate={{
                      y: [0, -30, 0],
                      x: [0, Math.random() * 20 - 10, 0],
                      scale: [0, 1, 0],
                      opacity: [0, 1, 0],
                    }}
                    transition={{
                      duration: 2,
                      repeat: Infinity,
                      delay: i * 0.2,
                      ease: "easeInOut"
                    }}
                  />
                ))}
              </div>

              {/* Verification badge */}
              <motion.div
                className="absolute top-4 right-4 w-8 h-8 bg-green-500 rounded-full flex items-center justify-center"
                initial={{ scale: 0 }}
                animate={isInView ? { scale: 1 } : {}}
                transition={{ delay: index * 0.1 + 0.5, type: "spring" }}
                whileHover={{ scale: 1.2, rotate: 360 }}
              >
                <motion.div
                  animate={{ rotate: 360 }}
                  transition={{ duration: 2, repeat: Infinity, ease: "linear" }}
                >
                  ✓
                </motion.div>
              </motion.div>
            </motion.div>
          ))}
        </div>

        {/* Call to action */}
        <motion.div
          className="text-center mt-20"
          initial={{ opacity: 0, y: 50 }}
          animate={isInView ? { opacity: 1, y: 0 } : {}}
          transition={{ delay: 1.5, duration: 1 }}
        >
          <motion.button
            whileHover={{ 
              scale: 1.05,
              boxShadow: "0 0 40px rgba(6, 182, 212, 0.5)"
            }}
            whileTap={{ scale: 0.95 }}
            className="px-12 py-4 bg-gradient-to-r from-cyan-600 to-purple-600 text-white rounded-full font-bold text-lg hover:from-cyan-500 hover:to-purple-500 transition-all duration-300 flex items-center gap-3 mx-auto"
          >
            <ExternalLink size={24} />
            View All Certificates
            <ArrowRight size={24} />
          </motion.button>
        </motion.div>
      </motion.div>
    </section>
  );
};

// Ultra-Enhanced Projects Section
const UltraProjects = () => {
  const ref = useRef(null);
  const isInView = useInView(ref, { once: true });
  const [selectedProject, setSelectedProject] = useState(null);
  const [filter, setFilter] = useState('all');

  const projects = [
    {
      id: 1,
      title: 'AI Portfolio Generator',
      description: 'Revolutionary AI-powered platform that transforms marketing vision into compelling case studies and winning proposals using advanced machine learning algorithms.',
      longDescription: 'This cutting-edge project leverages OpenAI\'s GPT models to automatically generate professional portfolios, case studies, and proposals. The system analyzes input data, understands context, and produces human-like content that resonates with target audiences.',
      tech: ['React', 'Node.js', 'OpenAI API', 'Tailwind CSS', 'MongoDB', 'Express'],
      category: 'AI/ML',
      image: '/api/placeholder/600/400',
      github: '#',
      live: '#',
      featured: true,
      status: 'completed',
      year: '2025',
      preview: {
        stats: ['1000+ Case Studies Generated', '500+ Proposals Created', '95% Success Rate', '50+ Happy Clients'],
        features: ['AI-Powered Generation', 'Custom Templates', 'Analytics Dashboard', 'Multi-language Support', 'Real-time Collaboration'],
        technologies: ['Natural Language Processing', 'Machine Learning', 'Cloud Computing', 'Responsive Design']
      },
      color: 'from-cyan-500 to-blue-500'
    },
    {
      id: 2,
      title: 'SentimentScope',
      description: 'Real-time social media sentiment analysis platform using Reddit posts and Gemini AI for comprehensive emotional intelligence insights.',
      longDescription: 'An advanced sentiment analysis tool that combines Reddit API data with Google\'s Gemini AI to provide real-time emotional intelligence insights. The platform processes thousands of posts per minute and provides detailed analytics.',
      tech: ['Python', 'Transformers', 'Reddit API', 'React', 'Chart.js', 'FastAPI'],
      category: 'Data Analytics',
      image: '/api/placeholder/600/400',
      github: '#',
      live: '#',
      featured: true,
      status: 'completed',
      year: '2024',
      preview: {
        stats: ['70% Reddit Data Processing', '30% Gemini AI Analysis', '99.9% Uptime', '1M+ Posts Analyzed'],
        features: ['Real-time Sentiment Analysis', 'Interactive Visualizations', 'Trend Prediction', 'Custom Dashboards', 'API Integration'],
        technologies: ['Natural Language Processing', 'Data Visualization', 'Real-time Processing', 'Machine Learning']
      },
      color: 'from-purple-500 to-pink-500'
    },
    {
      id: 3,
      title: 'Data Analytics Dashboard',
      description: 'Interactive business intelligence dashboard for comprehensive data visualization and advanced analytics with real-time insights.',
      longDescription: 'A comprehensive business intelligence solution that connects multiple data sources and provides interactive visualizations. Built with modern web technologies and optimized for performance.',
      tech: ['Tableau', 'Python', 'SQL', 'Power BI', 'D3.js', 'PostgreSQL'],
      category: 'Data Analytics',
      image: '/api/placeholder/600/400',
      github: '#',
      live: '#',
      featured: false,
      status: 'in-progress',
      year: '2024',
      preview: {
        stats: ['Multiple Data Sources', 'Real-time Updates', '50+ Custom KPIs', '24/7 Monitoring'],
        features: ['Interactive Charts', 'Drill-down Analysis', 'Export Reports', 'Mobile Responsive', 'Automated Alerts'],
        technologies: ['Business Intelligence', 'Data Visualization', 'Database Management', 'Web Development']
      },
      color: 'from-green-500 to-emerald-500'
    },
    {
      id: 4,
      title: 'ML Prediction Model',
      description: 'Advanced machine learning model for predictive analytics and forecasting with 95% accuracy rate using ensemble methods.',
      longDescription: 'A sophisticated machine learning pipeline that combines multiple algorithms to achieve high-accuracy predictions. The model is deployed in production and serves thousands of requests daily.',
      tech: ['Python', 'Scikit-learn', 'Pandas', 'NumPy', 'TensorFlow', 'Docker'],
      category: 'AI/ML',
      image: '/api/placeholder/600/400',
      github: '#',
      live: '#',
      featured: false,
      status: 'completed',
      year: '2024',
      preview: {
        stats: ['95% Accuracy Rate', '1M+ Data Points', 'Real-time Predictions', '99% Model Reliability'],
        features: ['Multiple Algorithms', 'Feature Engineering', 'Model Validation', 'AutoML Pipeline', 'Performance Monitoring'],
        technologies: ['Machine Learning', 'Deep Learning', 'Statistical Analysis', 'Model Deployment']
      },
      color: 'from-yellow-500 to-orange-500'
    },
    {
      id: 5,
      title: 'Smart City IoT Platform',
      description: 'IoT-based smart city management system for traffic optimization, energy management, and environmental monitoring.',
      longDescription: 'A comprehensive IoT platform that collects and analyzes data from various city sensors to optimize traffic flow, manage energy consumption, and monitor environmental conditions in real-time.',
      tech: ['Python', 'IoT Sensors', 'MQTT', 'InfluxDB', 'Grafana', 'React'],
      category: 'IoT',
      image: '/api/placeholder/600/400',
      github: '#',
      live: '#',
      featured: true,
      status: 'in-progress',
      year: '2025',
      preview: {
        stats: ['100+ IoT Sensors', '24/7 Monitoring', '30% Traffic Improvement', '20% Energy Savings'],
        features: ['Real-time Monitoring', 'Predictive Analytics', 'Alert System', 'Mobile App', 'API Gateway'],
        technologies: ['Internet of Things', 'Time Series Database', 'Real-time Analytics', 'Mobile Development']
      },
      color: 'from-indigo-500 to-purple-500'
    },
    {
      id: 6,
      title: 'Blockchain Voting System',
      description: 'Secure, transparent, and decentralized voting system using blockchain technology for enhanced electoral integrity.',
      longDescription: 'A revolutionary voting platform built on blockchain technology that ensures transparency, security, and immutability of votes. The system provides real-time results while maintaining voter privacy.',
      tech: ['Solidity', 'Web3.js', 'React', 'Ethereum', 'IPFS', 'MetaMask'],
      category: 'Blockchain',
      image: '/api/placeholder/600/400',
      github: '#',
      live: '#',
      featured: false,
      status: 'completed',
      year: '2024',
      preview: {
        stats: ['100% Transparent', 'Immutable Records', '99.99% Security', '1000+ Test Votes'],
        features: ['Decentralized Architecture', 'Smart Contracts', 'Real-time Results', 'Voter Verification', 'Audit Trail'],
        technologies: ['Blockchain', 'Smart Contracts', 'Cryptography', 'Decentralized Applications']
      },
      color: 'from-red-500 to-pink-500'
    }
  ];

  const categories = ['all', 'AI/ML', 'Data Analytics', 'IoT', 'Blockchain'];
  const filteredProjects = filter === 'all' ? projects : projects.filter(p => p.category === filter);

  return (
    <section ref={ref} className="py-32 px-8 lg:px-16 bg-gray-900/50 relative overflow-hidden" id="projects">
      {/* Animated background */}
      <div className="absolute inset-0">
        <motion.div
          animate={{
            backgroundPosition: ['0% 0%', '100% 100%'],
          }}
          transition={{
            duration: 20,
            repeat: Infinity,
            ease: "linear"
          }}
          className="absolute inset-0 opacity-30"
          style={{
            backgroundImage: `
              radial-gradient(circle at 25% 25%, rgba(6, 182, 212, 0.15) 0%, transparent 50%),
              radial-gradient(circle at 75% 75%, rgba(147, 51, 234, 0.15) 0%, transparent 50%)
            `
          }}
        />
      </div>

      <motion.div
        initial={{ opacity: 0 }}
        animate={isInView ? { opacity: 1 } : {}}
        transition={{ duration: 1 }}
        className="max-w-7xl mx-auto relative z-10"
      >
        <motion.div
          className="text-center mb-16"
          initial={{ opacity: 0, y: 100 }}
          animate={isInView ? { opacity: 1, y: 0 } : {}}
          transition={{ duration: 1, type: "spring" }}
        >
          <motion.h2 
            className="text-6xl lg:text-7xl font-black mb-8 relative inline-block"
          >
            <span className="bg-gradient-to-r from-cyan-400 via-purple-400 to-pink-400 bg-clip-text text-transparent">
              Featured Projects
            </span>
            <motion.div
              className="absolute -inset-4 bg-gradient-to-r from-cyan-500/20 to-purple-500/20 rounded-2xl blur-xl"
              animate={{
                scale: [1, 1.1, 1],
                opacity: [0.3, 0.6, 0.3],
              }}
              transition={{
                duration: 3,
                repeat: Infinity,
                ease: "easeInOut"
              }}
            />
          </motion.h2>
          
          <motion.p
            className="text-2xl text-gray-400 max-w-4xl mx-auto mb-8"
            initial={{ opacity: 0, y: 30 }}
            animate={isInView ? { opacity: 1, y: 0 } : {}}
            transition={{ delay: 0.3, duration: 1 }}
          >
            Innovative solutions that push the boundaries of technology and create meaningful impact
          </motion.p>

          {/* Category filters */}
          <motion.div
            className="flex flex-wrap justify-center gap-4 mb-8"
            initial={{ opacity: 0, scale: 0 }}
            animate={isInView ? { opacity: 1, scale: 1 } : {}}
            transition={{ delay: 0.5, duration: 1, type: "spring" }}
          >
            {categories.map((category) => (
              <motion.button
                key={category}
                onClick={() => setFilter(category)}
                whileHover={{ scale: 1.05 }}
                whileTap={{ scale: 0.95 }}
                className={`px-6 py-3 rounded-full font-semibold transition-all duration-300 ${
                  filter === category
                    ? 'bg-gradient-to-r from-cyan-600 to-purple-600 text-white'
                    : 'bg-gray-800/50 text-gray-400 hover:text-white hover:bg-gray-700/50'
                }`}
              >
                {category === 'all' ? 'All Projects' : category}
              </motion.button>
            ))}
          </motion.div>

          {/* Project stats */}
          <motion.div
            className="flex justify-center gap-12"
            initial={{ opacity: 0, y: 30 }}
            animate={isInView ? { opacity: 1, y: 0 } : {}}
            transition={{ delay: 0.7, duration: 1 }}
          >
            <div className="text-center">
              <div className="text-4xl font-bold text-cyan-400">{projects.length}</div>
              <div className="text-gray-500">Total Projects</div>
            </div>
            <div className="text-center">
              <div className="text-4xl font-bold text-purple-400">{projects.filter(p => p.featured).length}</div>
              <div className="text-gray-500">Featured</div>
            </div>
            <div className="text-center">
              <div className="text-4xl font-bold text-pink-400">{projects.filter(p => p.status === 'completed').length}</div>
              <div className="text-gray-500">Completed</div>
            </div>
          </motion.div>
        </motion.div>

        {/* Projects grid */}
        <motion.div 
          className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10"
          layout
        >
          <AnimatePresence>
            {filteredProjects.map((project, index) => (
              <motion.div
                key={project.id}
                layout
                initial={{ opacity: 0, y: 100, rotateX: -30 }}
                animate={{ opacity: 1, y: 0, rotateX: 0 }}
                exit={{ opacity: 0, y: -100, rotateX: 30 }}
                whileHover={{ 
                  scale: 1.05, 
                  rotateY: 5,
                  boxShadow: "0 0 60px rgba(6, 182, 212, 0.4)",
                  z: 20
                }}
                transition={{ 
                  delay: index * 0.1, 
                  duration: 0.8,
                  type: "spring",
                  stiffness: 100
                }}
                className="group bg-gray-800/80 backdrop-blur-sm border border-gray-700/50 rounded-3xl overflow-hidden hover:border-cyan-500/50 transition-all duration-500 cursor-pointer relative"
                onClick={() => setSelectedProject(project)}
              >
                {/* Project image/preview */}
                <div className={`h-64 bg-gradient-to-br ${project.color} relative overflow-hidden flex items-center justify-center`}>
                  <motion.div
                    className="text-8xl opacity-60"
                    whileHover={{ scale: 1.2, rotate: 10 }}
                    transition={{ duration: 0.5 }}
                  >
                    {project.category === 'AI/ML' ? '🤖' :
                     project.category === 'Data Analytics' ? '📊' :
                     project.category === 'IoT' ? '🌐' :
                     project.category === 'Blockchain' ? '⛓️' : '🚀'}
                  </motion.div>
                  
                  {/* Featured badge */}
                  {project.featured && (
                    <motion.div
                      className="absolute top-4 left-4 bg-gradient-to-r from-yellow-500 to-orange-500 text-white px-3 py-1 rounded-full text-sm font-bold flex items-center gap-1"
                      initial={{ scale: 0 }}
                      animate={{ scale: 1 }}
                      transition={{ delay: 0.5, type: "spring" }}
                    >
                      <Star size={14} />
                      Featured
                    </motion.div>
                  )}

                  {/* Status badge */}
                  <motion.div
                    className={`absolute top-4 right-4 px-3 py-1 rounded-full text-sm font-semibold ${
  project.status === 'completed' 
    ? 'bg-green-500/20 text-green-400 border border-green-500/30' 
    : 'bg-orange-500/20 text-orange-400 border border-orange-500/30'
}`}
initial={{ scale: 0 }}
animate={{ scale: 1 }}
transition={{ delay: 0.7, type: "spring" }}
>
  {project.status === 'completed' ? '✅ Complete' : '🔄 In Progress'}
</motion.div>
{/* Floating particles */}
{[...Array(6)].map((_, i) => (
  <motion.div
    key={i}
    className="absolute w-2 h-2 bg-white/30 rounded-full"
    style={{
      left: `${20 + i * 12}%`,
      top: `${30 + (i % 2) * 40}%`,
    }}
    animate={{
      y: [0, -20, 0],
      opacity: [0.3, 1, 0.3],
      scale: [1, 1.2, 1],
    }}
    transition={{
      duration: 3,
      repeat: Infinity,
      delay: i * 0.2,
