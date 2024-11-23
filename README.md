Sistema de Monitoramento e Alertas para Usinas Nucleares
Um sistema abrangente de monitoramento e alertas para operadores de usinas nucleares, com verificação automatizada de EPIs através de deep learning e visão computacional.
🌟 Visão Geral
Este sistema oferece monitoramento em tempo real de parâmetros críticos em usinas nucleares, implementando um módulo inovador de verificação de EPIs (Equipamentos de Proteção Individual). Combina tecnologias tradicionais de monitoramento com inteligência artificial para garantir a rigorosa adesão aos padrões de segurança nuclear.
Principais Características

Monitoramento em tempo real de parâmetros críticos (temperatura, pressão, níveis de radiação, sistemas de refrigeração)
Sistema de alertas em três níveis (normal, preventivo, crítico)
Verificação automatizada de EPIs usando deep learning
Integração com aplicativo móvel
Registro e relatórios completos de conformidade

🛡️ Sistema de Verificação de EPIs
O sistema implementa um módulo automatizado de verificação de EPIs utilizando Deep Learning e Visão Computacional, integrado ao sistema de controle de acesso da instalação.
Implementação Técnica

Framework: TensorFlow/Keras com OpenCV
Arquitetura: Redes Neurais Convolucionais (CNN)
Desenvolvimento Mobile: Kotlin

Métricas de Desempenho

mAP: 81,7%
Precisão na Detecção: 89,8%
Recall: 72,3%
Precisão na Detecção de Máscaras: 91%
Precisão na Detecção de Macacão: 72%

🔧 Metodologia de Implementação
1. Preparação do Dataset

Coleta de imagens de operadores utilizando EPIs
Anotação manual e integração com modelos do Roboflow universe
Técnicas de augmentação de dados
Divisão do dataset: 70% treino, 20% validação, 10% teste

2. Treinamento do Modelo

Transfer learning com modelos pré-treinados
Otimização de hiperparâmetros através de validação cruzada
Monitoramento de métricas de performance

3. Integração Mobile

Conversão do modelo para TensorFlow
Pipeline de pré-processamento de imagens
Interface de captura em tempo real
Sistema de feedback visual

💻 Funcionamento do Sistema
Fluxo de Verificação de Acesso

Operador se posiciona em frente à câmera do dispositivo móvel
Captura e processamento de imagem em tempo real
Detecção de EPIs pelo modelo de deep learning
Controle de acesso baseado nos resultados da verificação

Monitoramento e Registro

Integração com banco de dados Oracle
Registro de conformidade para auditorias
Geração automatizada de relatórios

🔐 Níveis de Segurança
O sistema implementa três níveis de segurança:

Normal: Estado de monitoramento regular
Preventivo: Monitoramento intensificado para potenciais problemas
Crítico: Necessidade de resposta imediata

📊 Benefícios

Redução de erro humano na verificação de EPIs
Maior conformidade com protocolos de segurança
Verificações de segurança automatizadas e auditáveis
Sistema de monitoramento e alertas em tempo real
Gestão integrada de segurança

Observação: Este sistema foi projetado para aplicações de segurança em usinas nucleares e requer certificação e aprovação adequadas antes da implantação em ambientes de produção.
