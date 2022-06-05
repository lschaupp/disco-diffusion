# Model prep phase, also cuts down on build context wait time since these models files
# are large and prone to take long to copy...
FROM disco-diffusion:5.2 AS modelmain

# Clone Git repositories
RUN git clone https://github.com/lschaupp/disco-diffusion